# European_Wine

1.) Description:
            In this project we have performed Exploratory data analysis on the data regarding Eropean Wine
            
            The goal of the analysis was to determine the factors which are responsible for a high quality wine
            
2.) Hypothesis: 
          We made this hypothesis, that more the people will get drunk, the more will be the rating it will get. 
          So we compared alcohol content in the wine against the other parameters and found relationship between them.
          

3.) Methdology: 
          Performed exploratory data analysis to clean and optimize the data as per our requirements.
          
          Using pairplots figured out the relation between two or more matrices of the data set about the wine:
                    
                    Like: increased Citric acid lowers the pH of the wine and increases the acidity

        3.1) Conclusion to justify the hypothesis:                 
   
                                      With the increase in the alcohol the quality of the wine increases:
                                      from this assesment we can say that people tend to like a certain wine if it makes them drunk faster

                                      With more alcohol the basisity of the Wine increases (.i.e. pH level increases):
                                      Since the bases are bitter in taste, we can say that, people are in the favour of the bitter taste of the wine. 
                                      And they don't want a wine which tastes acidic.
   
         3.2) Performed further analysis:
                                      To understand the relation between alcohol and other matrics of a quality wine: 
                                      
                                      Results:
                                              a) Alcohol and the pH show a realtion proportional to each other 
                                              b) Sulphur and chlorides as show a proportional realtionship 

                                              Since quality of the wine is being measured by the amount of the alohol it has:
                                                  we can build relationships of the matrices with respect to the Alcohol to make perfect woine sample:
                                                      1) alcohol and volatile_acidity are slighltly inverse in relationship
                                                      2) alcohol and chlorides are inversely related 
                                                      3) alcohol and total_sulfur_dioxide are inversely related 
                                                      4) alcohol and pH are directly proportional to each other we can say that the taste of the wine should be bitter and not sour i.e. acidic
                                                      
                                                      
4.) Final Result: 
            
            We used two types of regressions to predict the variables that are responsible for the quality of the wine:
            
           1)  Ordinary least square:
           2)  Logistic regression: 

                      Variables we are confident about:
                            chlorides
                            free sulfur dioxide
                            total sulfur dioxide
                            volatile acidity
                            sulphates

                       Variables we are not confident about:
                            pH
                            Citric acid 
                            density 
                            alcohol  
                            
                            
              The final results competely contradicts the results, hence we can say that our hypothesis was not right, because on applying prediction models,
              Alcohol and pH are those categories which we are least confident about.
                                                      
                                                      
                                                      
                                                      
                                                      
                                                      
                                                      
