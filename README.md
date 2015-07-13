# topic-modeling-tool-FR

Fork of topic-modeling-tool --token-regex option. Now generates UTF-8 html pages.

Added a regex field allowing to specify a custom --token-regex.
``` 
  //         String[] temp1 = {"--input",inputDir,"--output",collectionPath,"--keep-sequence"};
  //         String regex = "[\\p{L}\\p{P}]*\\p{L}";
            String regex = regexTfield.getText();
            String[] temp1 = {"--input", inputDir, "--output", collectionPath, "--keep-sequence", "--token-regex", regex};
``` 

# Use

Compile with maven or use the attached .jar file (in the "target" folder).

To compile with maven:
```
sudo mvn clean install 
``` 

# Thanks

Genchou von H and Stéphane Devaux for their technical insights.

# Acknowledgements

Original work by https://code.google.com/p/topic-modeling-tool/ and MALLET (http://mallet.cs.umass.edu)

Modified by Simon Hengchen (shengche@ulb.ac.be - http://homepages.ulb.ac.be/~shengche/) and Marijn Koolen (marijn.koolen@uva.nl - http://humanities.uva.nl/~mkoolen1)

Available at https://github.com/ulbstic/topic-modeling-tool-FR


Simon Hengchen is a PhD Candidate at the Université libre de Bruxelles and funded by a Belgian Science Policy (BELSPO) project, TIC-Belgium (http://www.tic.ugent.be).
