Title: Books Collected from Patrick Collison's Tweet
Date: 2017-11-13 20:43
Tags:
Category:
Slug: books-collected-from-patrick-collison-tweet
Summary:


Last Sunday when I opened up twitter, I saw [this tweet](https://twitter.com/patrickc/status/929862403763798016) from @patrickc.  Before followers started to reply, I thought this could be a really nice chain to follow.

@patrickc/status/929862403763798016

This also reminds me what I listened a few days ago from [this episode](https://www.indiehackers.com/podcast/036-david-darmanin-of-hotjar) with David Darmanin on [IndieHackers](https://www.indiehackers.com), where David mentioned that he asked people "What's your favourite 10 books?" and he tooke the top 10 common books to start reading.

I'm definitely interested in making a list of the books mentioned in this thread, but I'm a little reluctant to go through more than 600 tweets and copy them into a spreadsheet. Being a Data Scientist myself, first idea came to me was, can I automate this or maybe I can make this a fun exercise.

In this blog post, I'll only cover the top 10 mentioned books, as that's where I get to in my analysis. Other things I want to is to look at the authors, published time and genres of the books. I'll probably need to use Goodreads or someth other APIs to do that.

### Top 10 Mentioned Books

Let's jump to the result first. If you are interested in how to get this list, I covered a little at the end of this blog post. Personally I found many interesting books I haven't read before, and this was the biggest reason that I started the exercise.

<table class="table table-bordered">
  <tr>
   <thead>
     <td> Title </td>
     <td> Review </td>
     <td> Mentions </td>
   </thead>
  <td>
    <a href="https://www.amazon.com/Sapiens-Humankind-Yuval-Noah-Harari/dp/0062316095&tag=traintest06-20"> <img src="https://images-na.ssl-images-amazon.com/images/I/51zJS6PmxbL._SX333_BO1,204,203,200_.jpg" height="100" /> </a>
  </td>
  <td> <b><a href="https://www.amazon.com/Sapiens-Humankind-Yuval-Noah-Harari/dp/0062316095&tag=traintest06-20">Sapiens</a></b> by Yuval Noah Harari, which is a summer reading pick by Barack Obama, Bill Gates and Mark Zuckerberg. At the time of writing the blog, it's the fourth most read book on Amazon Charts.
  </td>
  <td> 20 </td>
  </tr>
  <tr>
    <td> 
      <a href="https://www.amazon.com/1984-Signet-Classics-George-Orwell/dp/0451524934&tag=traintest06-20"> <img src="https://images-na.ssl-images-amazon.com/images/I/31l24hBKHaL._SX280_BO1,204,203,200_.jpg" height="100" /> </a>
    </td>
    <td>
      <b><a href="https://www.amazon.com/1984-Signet-Classics-George-Orwell/dp/0451524934&tag=traintest06-20">1984</a></b> was George Orwell’s chilling prophecy about the future. And while 1984 has come and gone, his dystopian vision of a government that will do anything to control the narrative is timelier than ever.
    </td>
    <td> 19 </td>
  </tr>
  
  <tr>
    <td> 
      <a href="https://www.amazon.com/Thinking-Fast-Slow-Daniel-Kahneman/dp/0374533555&tag=traintest06-20"> <img src="https://images-na.ssl-images-amazon.com/images/I/41RtytNpsfL._SX332_BO1,204,203,200_.jpg" height="100" /> </a>
    </td>
    <td> 
      <b><a href="https://www.amazon.com/Thinking-Fast-Slow-Daniel-Kahneman/dp/0374533555&tag=traintest06-20">Thinking, Fast and Slow</a></b>.  Daniel Kahneman, the renowned psychologist and winner of the Nobel Prize in Economics, takes us on a groundbreaking tour of the mind and explains the two systems that drive the way we think. 
    </td>
    <td> 16 </td>
  </tr>
  
  <tr>
    <td> 
      <a href="https://www.amazon.com/Zero-One-Notes-Startups-Future/dp/0804139296&tag=traintest06-20"> <img src="https://images-na.ssl-images-amazon.com/images/I/41puRJbtwkL._SX331_BO1,204,203,200_.jpg" height="100" /> </a>
    </td>
    <td>
      <b><a href="https://www.amazon.com/Zero-One-Notes-Startups-Future/dp/0804139296&tag=traintest06-20">Zero To One</a></b>. The great secret of our time is that there are still uncharted frontiers to explore and new inventions to create. In Zero to One, legendary entrepreneur and investor Peter Thiel shows how we can find singular ways to create those new things.
    </td>
    <td> 14 </td>
  </tr>
  
  <tr>
    <td> 
      <a href="https://www.amazon.com/Holy-Bible-New-Living-Translation/dp/1414309473&tag=traintest06-20"> <img src="https://images-na.ssl-images-amazon.com/images/I/41h7kSsaYdL._SX324_BO1,204,203,200_.jpg" height="100" /> </a>
    </td>
    <td> 
      <b><a href="https://www.amazon.com/Holy-Bible-New-Living-Translation/dp/1414309473&tag=traintest06-20">Bible</a></b>. "We are pressed on every side by troubles, but we are not crushed. We are perplexed, but not driven to despair." 2 Corinthians 4:8
    </td>
    <td> 11 </td>
  </tr>
  
  <tr>
    <td> 
      <a href="https://www.amazon.com/Sapiens-Humankind-Yuval-Noah-Harari/dp/0062316095&tag=traintest06-20"> <img src="https://images-na.ssl-images-amazon.com/images/I/41D%2BJAzx5rL._SX329_BO1,204,203,200_.jpg" height="100" /> </a>
    </td>
    <td>
      <b><a href="https://www.amazon.com/Sapiens-Humankind-Yuval-Noah-Harari/dp/0062316095&tag=traintest06-20">Antifragile</a></b> is a standalone book in Nassim Nicholas Taleb’s landmark Incerto series, an investigation of opacity, luck, uncertainty, probability, human error, risk, and decision-making in a world we don’t understand.
    </td>
    <td> 11 </td>
  </tr>
  
  <tr>
    <td> 
      <a href="https://www.amazon.com/Brave-New-World-Aldous-Huxley/dp/0060850523&tag=traintest06-20"> <img src="https://images-na.ssl-images-amazon.com/images/I/41l%2B4UobkRL._SX325_BO1,204,203,200_.jpg" height="100" /> </a>
    </td>
    <td> 
      <b><a href="https://www.amazon.com/Brave-New-World-Aldous-Huxley/dp/0060850523&tag=traintest06-20">Brave New World</a></b>. Now more than ever: Aldous Huxley's enduring "masterpiece ... one of the most prophetic dystopian works of the 20th century" (Wall Street Journal) must be read and understood by anyone concerned with preserving the human spirit in the face of our "brave new world"
    </td>
    <td> 11 </td>
  </tr>
  
  <tr>
    <td> 
      <a href="https://www.amazon.com/Meditations-Thrift-Editions-Marcus-Aurelius/dp/048629823X&tag=traintest06-20"> <img src="https://images-na.ssl-images-amazon.com/images/I/51B7EclqLBL._SX311_BO1,204,203,200_.jpg" height="100" /> </a>
    </td>
    <td> 
      <b><a href="https://www.amazon.com/Meditations-Thrift-Editions-Marcus-Aurelius/dp/048629823X&tag=traintest06-20">Meditations</a></b>. One of the world's most famous and influential books, Meditations, by the Roman emperor Marcus Aurelius (A.D. 121–180), incorporates the stoic precepts he used to cope with his life as a warrior and administrator of an empire. 
    </td>
    <td> 11 </td>
  </tr>
  
  <tr>
    <td> 
      <a href="https://www.amazon.com/Guns-Germs-Steel-Fates-Societies/dp/0393354326&tag=traintest06-20"> <img src="https://images-na.ssl-images-amazon.com/images/I/5101H2lhtXL._SX329_BO1,204,203,200_.jpg" height="100" /> </a>
    </td>
    <td> 
      <b><a href="https://www.amazon.com/Guns-Germs-Steel-Fates-Societies/dp/0393354326&tag=traintest06-20">Guns Germs and Steel: The Fates of Human Societies</a></b>. In this "artful, informative, and delightful" (William H. McNeill, New York Review of Books) book, Jared Diamond convincingly argues that geographical and environmental factors shaped the modern world. 
    </td>
    <td> 11 </td>
  </tr>
  
  <tr>
    <td> 
      <a href="https://www.amazon.com/Selfish-Gene-Anniversary-Landmark-Science/dp/0198788606&tag=traintest06-20"> <img src="https://images-na.ssl-images-amazon.com/images/I/41BSMHjI39L._SX327_BO1,204,203,200_.jpg" height="100" /> </a>
    </td>
    <td> 
      <b><a href="https://www.amazon.com/Selfish-Gene-Anniversary-Landmark-Science/dp/0198788606&tag=traintest06-20">The Selfish Gene</a></b>. Professor Dawkins articulates a gene's eye view of evolution - a view giving centre stage to these persistent units of information, and in which organisms can be seen as vehicles for their replication.
    </td>
    <td> 10 </td>
  </tr>
</table>

### What did I do?
First thing to do is getting access to Twitter API. I chose to use the library [python-twitter](https://github.com/bear/python-twitter) and obtained access tokens from [Twitter Developer](https://developer.twitter.com/). 

```python
    api = twitter.Api(
        consumer_key=CONSUMER_KEY,
        consumer_secret=CONSUMER_SECRET,
        access_token_key=ACCESS_TOKEN,
        access_token_secret=ACCESS_TOKEN_SECRET,
        sleep_on_rate_limit=True)
```
Once you have this, it's pretty easy to obtain a single status or tweet. For example, the post by @patrickc has `status_id =  '929862403763798016'`. To get the status via the API is as simple as

```python
    api.GetStatus('929862403763798016') 
```

and it returns something like this
```
Status(ID=929862403763798016, ScreenName=patrickc, Created=Mon Nov 13 00:04:07 +0000 2017, Text='So, Sunday evening Twitter: which five books have influenced you the most? (In terms of shaping your worldview.)')
```
However, it took me some time to get all the replies to this post, mainly because the Twitter API itself doesn't support this directly. I googled a little bit and ended up with [this gist](https://gist.github.com/edsu/54e6f7d63df3866a87a15aed17b51eaf), where you can search all tweets sent to some user from some `since_id` to `max_id`.

```
query = urllib.parse.urlencode({
    "q": "to:@%s" % user,
    "count": 100,
    "since_id": since_id,
    "max_id": max_id,
    "tweet_mode": "extended"
})

replies = api.GetSearch(raw_query=query, result_type='recent')
```
The code snippet is slightly different from the gist, because I had to make some change to make it work. Most important piece is `"tweet_mode": "extended"`, which guarantees that you will receive the full tweet rather than a truncated version with link to the original tweet. After this, I did lots of `re.sub`, `re.split` and `strip` calls to process the text and I have something cleaner to work with.
