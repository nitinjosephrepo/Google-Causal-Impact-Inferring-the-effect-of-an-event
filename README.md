## Infer the effects of an event(*e.g new campaign launch, website redesign*) using Google's Causal Impact model

### What is Causal Impact Analysis?
Causal Impact Analysis can reduce the noise and provide real statistical insight into your efforts giving you the confidence to move forward with, or revert, marketing initiatives.
The Causal Impact model lets you examine ecommerce and marketing time series data to understand whether changes have led to a statistically significant performance improvement. Here's we use PyCausalImpact to analyse changes to 
Boeing Stock price after Flight 302 Aircrash. I have used publicly availaible datasets here for analysis as using clients marketing data come with 
potential privacy concerns. 

### Applications of causal impact modeling in marketing

Some potential applications for this in Digital marketing:
 1. SEO testing: Did changes to the site have a statistically significant impact upon SEO?
 2. Price changes: Has a change in price had a positive or negative impact upon a specific metric?
 3. Site features: Did the addition or removal of a site feature have an impact upon the site performance?
 4. Promotional campaigns: Did a promotion starting or ending have a significant impact on sales?
 
 ### Additional Resources on Google's CausalImpact

  - https://google.github.io/CausalImpact/CausalImpact.html
  - https://research.google/pubs/pub41854/
  - https://cran.r-project.org/web/packages/CausalImpact/vignettes/CausalImpact.html
  

 ### Examining the model outputs
 
 In our example we are inferring the impact the crash of Ethiopian Airlines Flight 302 had on Boeing Stock
 
 ![Screen Shot 2023-01-03 at 8 49 11 PM](https://user-images.githubusercontent.com/80999165/210486639-91e7c0a0-04a7-43ae-8cf9-200abed5ae2b.png)
 
 Our model output is showing that if Flight 302 had not crashed Boeing's stock price was expected to be $422.58, 95% CI [397.63, 446.98] but actual stock price in our period of 
 analysis was $369.48. Thus the impact of the accident on Boeing's stock was -$53.1
 
 
