# Page Metrics Tutorial

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fxdvrx1%2Fpage-metrics-tutorial&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=PAGE+VIEWS&edge_flat=false)](https://hits.seeyoufarm.com)

GitHub has its own `Traffic` to show unique visitors, views, etc.
But this one is not so useful. First, there is no total views,
as in total from the very start. Second, visitors cannot see
that, compared to YouTube, views are very important 
and it's placed there below the video.

Google Analytics is another option. But, first you need
to turn your repo as a web page. Second, the setup
is very tedious. It's really the best way but when it comes
to simplicity, this is not the best.

## The HITS Page Counter Service
So, I did not stop looking for the exact answer. 
Then I discovered HITS service to simply count
the visitors of your page or repo. Every page
hit will be counted and the best thing is
you can embed that on your page or repo README
file.

Visit the site: <https://hits.seeyoufarm.com/>.
That is where you generate the badge.

Step 1: Paste your URL.
![step 1](https://github.com/xdvrx1/page-metrics-tutorial/blob/main/screenshots/step1.png)

Step 2: Change the settings. For me, the
most important one is the words to be displayed,
instead of `hits`, I'll change that to `PAGE VIEWS`.
![step 2](https://github.com/xdvrx1/page-metrics-tutorial/blob/main/screenshots/step2.png)

Step 3: Get the embed code, for README file use 
the provided markdown code, for HTML use the 
provided html code.
![step 3](https://github.com/xdvrx1/page-metrics-tutorial/blob/main/screenshots/step3.png)

Paste it at the README file of your repo or web page. If ever you used the 
`master` branch as your page also, there is no need to add that separately.
And that's it!
![sample](https://github.com/xdvrx1/page-metrics-tutorial/blob/main/screenshots/final.png)

## How It Works
The service will count every page hit, meaning every request
for that particular URL will be counted, including yours.
You can test that by reloading the page or repo.
If the counter is incrementing for every reload,
it's working.

Take note, this is not using any data from GitHub or
Google Analytics, it's simply a page counter that
will record how many times a page or repo is requested.

Of course, this one can be faked easily. But, there is no sense faking
the views, right? You install it for the very reason you need to see
the total visitors. Why would you fake it? 
Unless you want to cheat yourself. 

You can visit the app development: 
<https://github.com/gjbae1212/hit-counter>
