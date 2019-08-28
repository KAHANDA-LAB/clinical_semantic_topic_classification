# clinical_semantic_topic_classification

There are 18 transcripts in 2 files:

| Filename           | # Transcripts  |
|:-------------------|---------------:|
| AS M2 RA WTH.tsv   |             5  |
| Matt M2 RA WTH.tsv |             13 |

Class Labels:
1. Chief Complaint
2. Client Details
3. Family History
4. Medical History
5. Social History
6. Others

Each line contains a sample and one of the six class labels separated by a tab character. Any line starting with a pound sign (#), also known as number sign and hash, denotes a comment and should be ignored while reading the samples from the files. However, there is only one comment per transcript and it appears as the first line of the transcript. Each comment includes two words, first: source name (Matt or AS) and second: transcript identifier, that can be used for debugging purpose or to generate transcript-wise statistics.
