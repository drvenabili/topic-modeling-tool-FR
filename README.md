# topic-modeling-tool-FR

Fork of topic-modeling-tool with hardcoded --token-regex option. Works with French. Now generates UTF-8 html pages.

Added on lines 540-543 of /src/main/java/cc/mallet/topics/gui/TopicModelingTool.java:
``` 
  //         String[] temp1 = {"--input",inputDir,"--output",collectionPath,"--keep-sequence"};
            String regex = "[\\p{L}\\p{P}]*\\p{L}";
            String[] temp1 = {"--input", inputDir, "--output", collectionPath, "--keep-sequence", "--token-regex", regex};
``` 

# Use

Compile with maven or use the attached .jar file (in the "target" folder).

To compile with maven:
```
sudo mvn clean install 
``` 

# Thanks

Genchou von H for his technical insights

# Acknowledgments

Original work by https://code.google.com/p/topic-modeling-tool/ and MALLET (http://mallet.cs.umass.edu)

Modified to accept diacritics and accents (--token-regex "[\\p{L}\\p{P}]*\\p{L}") by Simon Hengchen (shengche@ulb.ac.be - http://homepages.ulb.ac.be/~shengche/)
Available at https://github.com/ulbstic/topic-modeling-tool-FR

Simon Hengchen is a PhD Candidate at the Université libre de Bruxelles and funded by a Belgian Science Policy (BELSPO) project, TIC-Belgium (http://www.tic.ugent.be).
