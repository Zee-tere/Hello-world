# Tweet-Analysis

An analysis of data sourced from twitter and a .tsv file containing information about dogs rated on '@weratedogs' twitter profile. Task was to explore and identify tidiness and quality issues and fix a couple of them.

## Dataset

The data consisted of data sourced from twitter and a supporting CSV file located https://d17h27t6h515a5.cloudfront.net/topher/2017/August/59a4e958_twitter-archive-enhanced/twitter-archive-enhanced.csv and here https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv. I imported the data from all the required sources and while doing that, I encountered a couple of challenges that probably affected my dataset especially my Image prediction data. It caused a lot of delay because I spent a lot of time figuring out what was wrong and how to take care of it. I visually and programmatically assessed my Data and I was able to discover some issues.

## Summary of Findings

In my exploration I discovered some major Tidiness and quality Issues:

In my “Tweets” Table I noted one - Date and timestamps were in the same column and should be separated.

In my “Twitter_archive_enhanced” table I also noted one - Dogstages were scattered in different columns. I also noted that Information about one type of observational unit is spread across 3 different files

For the Quality issues I noted one in my “Tweets” Table and seven in my “Twitter_archive_enhanced” table.

For my Tweets column I noted

The "+00:00" attached to the date and time in the Timestamp columns

For my “Twitter_archive_enhanced” table I noted:

The column names were not well presented and lacked an order

There were tweet entries with incorrect names in the table ('None', 'such', 'a', 'not', 'one', 'mad', 'an', 'very', 'my', 'his', 'actually', 'his', 'getting', 'unacceptable', 'all', 'old', 'infuriating', 'the', 'by', 'officially', 'light', 'space').

There were Absurd numbers in the “Rating rating_numerator” column

There were Rating_denominator above and below 10

The addition of 'href=' in the source column.

The addition of "+00:00" in the Timestamp columns.

The Missing Dog names represented with “None”

The Missing expanded_urls.

Retweets were included in the Dataset
