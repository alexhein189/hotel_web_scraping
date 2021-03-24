# hotel_web_scraping
The Flask web application goes through six website articles and scrapes relevant content related to MYKONOS BLU hotel


The web application through a Flask backend displays relevant information scraped from seven websites provided in the documentation regarding the hotel "Mykonos Blu Grecotel Exclusive Resort" located in Psarou, Greece into JSON format. 

The application uses the Scrapy library from Python in order to scrape the appropriate information. This is achieved by creating Spiders for each of the seven articles and then using them to crawl the data. The crawling of the data (the extraction) is achieved using the CrawlProcess library, instantiating a CrawlProcesser class.

The main app.py script uses Flask to build the web application and uses Process another Python library in order to run the CrawlerProcessors for each of the seven articles in parallel to another. 

Below is the output of the scraping on the web application.

{
  "data": [
    {
      "article_date": "10th September 2019", 
      "article_image": "https://dynaimage.cdn.cnn.com/cnn/e_blur:500,q_auto:low,w_50,c_fill,g_auto,h_28,ar_16:9/http%3A%2F%2Fcdn.cnn.com%2Fcnnnext%2Fdam%2Fassets%2F190903131748-greek-luxury-seaside-hotels---grecotel-mykonos-blu---infinity-pool-1.jpg", 
      "article_lang": "en", 
      "article_status": "HIGH", 
      "article_summary": "Perfectly located on the sandy Psarou Beach, Mykonos Blu is comprised of beautiful island bungalows and private villas with mesmerizing views of the Aegean Sea.", 
      "article_title": "10 of the best luxury seaside hotels in Greece | CNN Travel", 
      "hotel_id": "25452876"
    }, 
    {
      "article_date": null, 
      "article_image": "https://content.api.news/v3/images/bin/eb19b705183c72333d1d6f45f09875c8?width=650", 
      "article_lang": "en-GB", 
      "article_status": "MEDIUM", 
      "article_summary": " Whitewashed cycladic-style bungalows? Glistening Aegean views from the privacy of your own plunge pool? A private beach with attentive staff serving the freshest Greek cuisine and drinks? Check, check and check. Perched on a rocky ledge that juts out over the sea is ", 
      "article_title": "18 places for romance", 
      "hotel_id": "25452876"
    }, 
    {
      "article_date": null, 
      "article_image": null, 
      "article_lang": "en-GB", 
      "article_status": "MEDIUM", 
      "article_summary": "Less than 10 minutes' drive from Mykonos Town, the sea and sun-bathed Mykonos Blu complex contains 105 rooms and 15 villa suites, arranged along the island's romantically rugged hillside", 
      "article_title": "Travel Guide To Mykonos", 
      "hotel_id": "25452876"
    }, 
    {
      "article_date": "2019", 
      "article_image": "https://media.cntraveler.com/photos/59cd59680dcd49375c38402c/16:9/w_2560%2Cc_limit/View3-MykonosBlu-Greece-CRHotel.jpg", 
      "article_lang": "en-us", 
      "article_status": "MEDIUM", 
      "article_summary": null, 
      "article_title": "Mykonos Blu", 
      "hotel_id": "25452876"
    }, 
    {
      "article_date": null, 
      "article_image": null, 
      "article_lang": "en-GB", 
      "article_status": "MEDIUM", 
      "article_summary": "Less than 10 minutes' drive from Mykonos Town, the sea and sun-bathed Mykonos Blu complex contains 105 rooms and 15 villa suites, arranged along the island's romantically rugged hillside", 
      "article_title": "Travel Guide To Mykonos", 
      "hotel_id": "25452876"
    }, 
    {
      "article_date": null, 
      "article_image": null, 
      "article_lang": "en", 
      "article_status": "LOW", 
      "article_summary": null, 
      "article_title": "Athens travel guide", 
      "hotel_id": "25452876"
    }
  ]
}






Instructions on running the programme

1.	In order to run the application, please install the requirements as stated in the requirements.txt file. 

2.	Then run python app.py on terminal.


