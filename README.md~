# topic-modeling-tool-FR

Fork of topic-modeling-tool with hardcoded --token-regex option. Works with French.

Added on lines 540-543 of /src/main/java/cc/mallet/topics/gui/TopicModelingTool.java:
``` 
  //         String[] temp1 = {"--input",inputDir,"--output",collectionPath,"--keep-sequence"};
            String regex = "[\\p{L}\\p{P}]*\\p{L}";
            String[] temp1 = {"--input", inputDir, "--output", collectionPath, "--keep-sequence", "--token-regex", regex};
``` 

# Use

Compile with maven or use the attached .jar file.

# Original work by

https://code.google.com/p/topic-modeling-tool and of course MALLET
