# Pandas-Homework

## Here is a use case example of utilizing pandas for EDA, Data Cleaning, and lastly visualizing datasets. ##

 - The first step is loading the datasets as DateFrames from CSV files while simultaniously seeting the index for timeseries analysis.
 
 [Laoding data and fixing date](<blockquote class="imgur-embed-pub" lang="en" data-id="63CZpqC"><a href="https://imgur.com/63CZpqC">View post on imgur.com</a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>)
 
 - Removing the $ with replace which will cause issues for pandas being that it sees those values as strings.
  
  [sp500 .head()](<blockquote class="imgur-embed-pub" lang="en" data-id="uzLAJ5k"><a href="https://imgur.com/uzLAJ5k">View post on imgur.com</a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>)

 - Here the power of pandas is again evident with how easy it is to join Dataframes of data that wasn't pulled via SQL
 
 [concat photo](<blockquote class="imgur-embed-pub" lang="en" data-id="a4QTOef"><a href="https://imgur.com/a4QTOef">View post on imgur.com</a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>)
 
  - Utilizing EWM is a simple process with pandas as shown below, done all in one line of code
  
  [EWM](<blockquote class="imgur-embed-pub" lang="en" data-id="tRAzLSE"><a href="https://imgur.com/tRAzLSE">View post on imgur.com</a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>)
  
   - Next I was tasked with choosing my own portoflio, since hindsight is 20/20 I went with three stocks that outperformed every portfolio, 
   
   [my stocks](<blockquote class="imgur-embed-pub" lang="en" data-id="jpzLQxL"><a href="https://imgur.com/jpzLQxL">View post on imgur.com</a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>)
 
  - Bringing my picks together calculating pct_change along the row and joing all three stocks into one portfolio
  
  [joing pandas](<blockquote class="imgur-embed-pub" lang="en" data-id="hkeLgRe"><a href="https://imgur.com/hkeLgRe">View post on imgur.com</a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>)
  
   - Utilizing Sharpe ratios to compare risk vs. returns against my portfolio which still lost out to the Algo 1 portfolio, I'll get them next time!
   
   [sharpe](<blockquote class="imgur-embed-pub" lang="en" data-id="G7n5n6H"><a href="https://imgur.com/G7n5n6H">View post on imgur.com</a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>)
   
   # This Assignment stressed Importing Data with just one of the many pandas techniques to do so, EDA, Normalizing the data for comparison and using some basic visualization techniques that come with panndas.
