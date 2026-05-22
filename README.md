This project can be implements a plagiarism detection tool by comparing text files in your directory.

Here is a brief breakdown of how it works:

File Selection: The script identifies all files ending with a .txt extension in the current working directory.

Vectorization: It uses TfidfVectorizer to convert the text content of these files into numerical vectors. This method weights words by their importance, making it effective for comparing document content.

Similarity Calculation: It calculates the Cosine Similarity between every pair of text files. This produces a score between 0 (no similarity) and 1 (identical).

Sorting and Reporting: Finally, the script sorts the resulting pairs by their similarity scores in descending order and prints them, allowing you to quickly identify which files share the most similar content.
