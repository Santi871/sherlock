Sherlock
========

Extract interesting information about redditors from their submissions and comments. Outputs data in JSON format.

Dependencies
============
* [pytz](https://pypi.python.org/pypi/pytz/)
* [TextBlob 0.9.0](http://textblob.readthedocs.org/en/dev/)

Setup
=====
* Run `pip install -r requirements.txt` to install dependencies.
* Run `python -m textblob.download_corpora` to download TextBlob corpora.

Usage
=====
    python sherlock.py <reddit-username>
    
Example
=======
Command:

    python sherlock.py orionmelt

Output:

    Processing user orionmelt
	{"username": "orionmelt", "summary": {"first_post_date": 1407428328, "submissions": {"count": 29, "gilded": 0, "worst": {"permalink": "http://www.reddit.com/r/mydaily3_sandbox/comments/3ej7rl/test_post_please_ignore/", "title": "Test post, please ignore"}, "average_karma": 63.0, "computed_karma": 1832, "type_domain_breakdown": {"name": "All", "children": [{"name": "Self", "children": [{"name": "TheoryOfReddit", "size": 1}, {"name": "DestinyTheGame", "size": 1}, {"name": "harrypotter", "size": 1}, {"name": "Favors", "size": 1}, {"name": "blackmirror", "size": 1}, {"name": "golang", "size": 1}, {"name": "startups", "size": 2}, {"name": "Python", "size": 1}, {"name": "learnpython", "size": 1}, {"name": "roastmystartup", "size": 1}, {"name": "psych", "size": 1}, {"name": "mydaily3_sandbox", "size": 1}, {"name": "chrome", "size": 1}, {"name": "snoovatars", "size": 1}, {"name": "SideProject", "size": 1}]}, {"name": "Image", "children": []}, {"name": "Video", "children": []}, {"name": "Other", "children": [{"name": "snoopsnoo.com", "size": 7}, {"name": "triviusgame.com", "size": 1}, {"name": "blog.snoopsnoo.com", "size": 5}]}]}, "best": {"permalink": "http://www.reddit.com/r/dataisbeautiful/comments/2r3jnk/your_reddit_activity_analyzed_and_visualized_oc/", "title": "Your reddit activity, analyzed and visualized [OC]"}, "all_time_karma": 1070}, "signup_date": 1404973258, "comments": {"worst": {"text": "Just refreshed your SnoopSnoo profile, and it looks like it is now caught up with most of what you mentioned. :)", "permalink": "http://www.reddit.com/r/dataisbeautiful/comments/46xd0w/_/d0bb25n"}, "average_karma": 3.0, "best": {"text": "I built this site and posted on /r/dataisbeautiful and someone suggested that I crosspost it here. Feedback and criticism are welcome!", "permalink": "http://www.reddit.com/r/secretsanta/comments/2r7xhr/_/cnd9lyd"}, "count": 431, "gilded": 1, "hours_typed": 5.98, "unique_word_count": 1963, "all_time_karma": 844, "computed_karma": 1305, "total_word_count": 14344, "karma_per_word": 0.09}, "lurk_period": {"to": 1428638447, "from": 1426913740}}, "metrics": {"topic": {"name": "All", "children": [{"name": "Technology", "children": [{"name": "Internet", "children": [{"name": "Generic", "size": 129}]}, {"name": "Data", "children": [{"name": "Data Visualization", "size": 37}]}, {"name": "Programming", "children": [{"name": "Python", "size": 28}, {"name": "Generic", "size": 11}, {"name": "Web Development", "size": 2}]}, {"name": "Software", "children": [{"name": "Chrome", "size": 2}]}]}, {"name": "Other", "size": 49}, {"name": "Lifestyle", "children": [{"name": "Gifts and Charity", "children": [{"name": "Generic", "size": 37}]}, {"name": "Self-help and Motivation", "children": [{"name": "Generic", "size": 7}]}, {"name": "Relationships", "children": [{"name": "Generic", "size": 6}]}]}, {"name": "Business", "children": [{"name": "Entrepreneurship", "children": [{"name": "Generic", "size": 37}]}]}, {"name": "Gaming", "children": [{"name": "Generic", "children": [{"name": "Generic", "size": 24}]}, {"name": "Video Games", "children": [{"name": "Kerbal Space Program", "size": 2}, {"name": "Destiny", "size": 1}]}]}, {"name": "Meta", "children": [{"name": "Generic", "children": [{"name": "Generic", "size": 24}]}]}, {"name": "General", "children": [{"name": "Generic", "children": [{"name": "Generic", "size": 20}]}, {"name": "Discussion", "children": [{"name": "Generic", "size": 11}, {"name": "Personal Narratives", "size": 1}]}, {"name": "Memes", "children": [{"name": "Generic", "size": 6}]}, {"name": "Pictures", "children": [{"name": "Generic", "size": 3}]}, {"name": "Humor and Parody", "children": [{"name": "Generic", "size": 3}]}, {"name": "Videos", "children": [{"name": "Generic", "size": 2}]}]}, {"name": "News and Politics", "children": [{"name": "Generic", "children": [{"name": "Generic", "size": 3}]}, {"name": "World News", "children": [{"name": "Generic", "size": 2}]}]}, {"name": "Entertainment", "children": [{"name": "Television", "children": [{"name": "Psych", "size": 3}, {"name": "Seinfeld", "size": 2}, {"name": "British TV", "size": 1}]}, {"name": "Books", "children": [{"name": "Harry Potter", "size": 3}]}, {"name": "Comics", "children": [{"name": "Webcomics", "size": 2}]}]}, {"name": "Locations", "children": [{"name": "World", "children": [{"name": "Singapore", "size": 1}]}]}, {"name": "Sports", "children": [{"name": "Hockey", "children": [{"name": "New Jersey Devils", "size": 1}]}]}]}, "recent_karma": [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 191, 53, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 11, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 3, 0, 2, 0, 3, 1, 1, 0, 0, 0, 0], "weekday": [{"submission_karma": 28, "posts": 103, "comments": 99, "comment_karma": 229, "weekday": "Sun", "submissions": 4, "karma": 257}, {"submission_karma": 344, "posts": 54, "comments": 46, "comment_karma": 148, "weekday": "Mon", "submissions": 8, "karma": 492}, {"submission_karma": 194, "posts": 65, "comments": 62, "comment_karma": 179, "weekday": "Tue", "submissions": 3, "karma": 373}, {"submission_karma": 198, "posts": 62, "comments": 58, "comment_karma": 132, "weekday": "Wed", "submissions": 4, "karma": 330}, {"submission_karma": 563, "posts": 63, "comments": 59, "comment_karma": 197, "weekday": "Thu", "submissions": 4, "karma": 760}, {"submission_karma": 499, "posts": 57, "comments": 53, "comment_karma": 249, "weekday": "Fri", "submissions": 4, "karma": 748}, {"submission_karma": 6, "posts": 56, "comments": 54, "comment_karma": 171, "weekday": "Sat", "submissions": 2, "karma": 177}], "hour": [{"submission_karma": 0, "hour": 0, "posts": 24, "comments": 24, "comment_karma": 96, "karma": 96, "submissions": 0}, {"submission_karma": 4, "hour": 1, "posts": 14, "comments": 13, "comment_karma": 38, "karma": 42, "submissions": 1}, {"submission_karma": 0, "hour": 2, "posts": 11, "comments": 11, "comment_karma": 42, "karma": 42, "submissions": 0}, {"submission_karma": 20, "hour": 3, "posts": 22, "comments": 18, "comment_karma": 38, "karma": 58, "submissions": 4}, {"submission_karma": 13, "hour": 4, "posts": 30, "comments": 28, "comment_karma": 99, "karma": 112, "submissions": 2}, {"submission_karma": 0, "hour": 5, "posts": 33, "comments": 32, "comment_karma": 68, "karma": 68, "submissions": 1}, {"submission_karma": 0, "hour": 6, "posts": 35, "comments": 35, "comment_karma": 90, "karma": 90, "submissions": 0}, {"submission_karma": 0, "hour": 7, "posts": 26, "comments": 26, "comment_karma": 80, "karma": 80, "submissions": 0}, {"submission_karma": 1, "hour": 8, "posts": 29, "comments": 28, "comment_karma": 50, "karma": 51, "submissions": 1}, {"submission_karma": 0, "hour": 9, "posts": 23, "comments": 23, "comment_karma": 41, "karma": 41, "submissions": 0}, {"submission_karma": 0, "hour": 10, "posts": 5, "comments": 5, "comment_karma": 15, "karma": 15, "submissions": 0}, {"submission_karma": 179, "hour": 11, "posts": 4, "comments": 3, "comment_karma": 5, "karma": 184, "submissions": 1}, {"submission_karma": 12, "hour": 12, "posts": 7, "comments": 6, "comment_karma": 15, "karma": 27, "submissions": 1}, {"submission_karma": 512, "hour": 13, "posts": 7, "comments": 5, "comment_karma": 62, "karma": 574, "submissions": 2}, {"submission_karma": 0, "hour": 14, "posts": 8, "comments": 8, "comment_karma": 17, "karma": 17, "submissions": 0}, {"submission_karma": 60, "hour": 15, "posts": 16, "comments": 14, "comment_karma": 29, "karma": 89, "submissions": 2}, {"submission_karma": 7, "hour": 16, "posts": 16, "comments": 14, "comment_karma": 32, "karma": 39, "submissions": 2}, {"submission_karma": 0, "hour": 17, "posts": 19, "comments": 19, "comment_karma": 29, "karma": 29, "submissions": 0}, {"submission_karma": 524, "hour": 18, "posts": 20, "comments": 16, "comment_karma": 111, "karma": 635, "submissions": 4}, {"submission_karma": 300, "hour": 19, "posts": 16, "comments": 13, "comment_karma": 88, "karma": 388, "submissions": 3}, {"submission_karma": 12, "hour": 20, "posts": 22, "comments": 20, "comment_karma": 59, "karma": 71, "submissions": 2}, {"submission_karma": 185, "hour": 21, "posts": 24, "comments": 22, "comment_karma": 61, "karma": 246, "submissions": 2}, {"submission_karma": 0, "hour": 22, "posts": 25, "comments": 25, "comment_karma": 86, "karma": 86, "submissions": 0}, {"submission_karma": 3, "hour": 23, "posts": 24, "comments": 23, "comment_karma": 54, "karma": 57, "submissions": 1}], "recent_activity_heatmap": "00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000010000000000000000010000008f000010000000000100000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000f00000000000000000000000000000000000000000000000010000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000f00000000000000000000000000000010000000000000000000000000000000000000000000000000000000000101000000000000000000000000001000100000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000", "date": [{"submission_karma": 0, "posts": 1, "comments": 1, "comment_karma": 1, "karma": 1, "date": "2014-07-01", "submissions": 0}, {"submission_karma": 4, "posts": 12, "comments": 11, "comment_karma": 16, "karma": 20, "date": "2014-08-01", "submissions": 1}, {"submission_karma": 0, "posts": 0, "comments": 0, "comment_karma": 0, "karma": 0, "date": "2014-09-01", "submissions": 0}, {"submission_karma": 0, "posts": 0, "comments": 0, "comment_karma": 0, "karma": 0, "date": "2014-10-01", "submissions": 0}, {"submission_karma": 0, "posts": 0, "comments": 0, "comment_karma": 0, "karma": 0, "date": "2014-11-01", "submissions": 0}, {"submission_karma": 291, "posts": 39, "comments": 38, "comment_karma": 166, "karma": 457, "date": "2014-12-01", "submissions": 1}, {"submission_karma": 988, "posts": 112, "comments": 109, "comment_karma": 412, "karma": 1400, "date": "2015-01-01", "submissions": 3}, {"submission_karma": 5, "posts": 72, "comments": 71, "comment_karma": 173, "karma": 178, "date": "2015-02-01", "submissions": 1}, {"submission_karma": 12, "posts": 31, "comments": 28, "comment_karma": 96, "karma": 108, "date": "2015-03-01", "submissions": 3}, {"submission_karma": 12, "posts": 39, "comments": 37, "comment_karma": 110, "karma": 122, "date": "2015-04-01", "submissions": 2}, {"submission_karma": 4, "posts": 11, "comments": 10, "comment_karma": 21, "karma": 25, "date": "2015-05-01", "submissions": 1}, {"submission_karma": 0, "posts": 1, "comments": 1, "comment_karma": 1, "karma": 1, "date": "2015-06-01", "submissions": 0}, {"submission_karma": 15, "posts": 11, "comments": 8, "comment_karma": 14, "karma": 29, "date": "2015-07-01", "submissions": 3}, {"submission_karma": 0, "posts": 7, "comments": 7, "comment_karma": 20, "karma": 20, "date": "2015-08-01", "submissions": 0}, {"submission_karma": 92, "posts": 64, "comments": 56, "comment_karma": 107, "karma": 199, "date": "2015-09-01", "submissions": 8}, {"submission_karma": 180, "posts": 31, "comments": 29, "comment_karma": 74, "karma": 254, "date": "2015-10-01", "submissions": 2}, {"submission_karma": 13, "posts": 4, "comments": 2, "comment_karma": 34, "karma": 47, "date": "2015-11-01", "submissions": 2}, {"submission_karma": 0, "posts": 4, "comments": 4, "comment_karma": 10, "karma": 10, "date": "2015-12-01", "submissions": 0}, {"submission_karma": 216, "posts": 9, "comments": 7, "comment_karma": 28, "karma": 244, "date": "2016-01-01", "submissions": 2}, {"submission_karma": 0, "posts": 12, "comments": 12, "comment_karma": 22, "karma": 22, "date": "2016-02-01", "submissions": 0}], "common_words": [{"text": "feedback", "size": 76}, {"text": "data", "size": 58}, {"text": "site", "size": 57}, {"text": "comments", "size": 56}, {"text": "reddit", "size": 54}, {"text": "questions", "size": 50}, {"text": "ha", "size": 41}, {"text": "game", "size": 40}, {"text": "posts", "size": 39}, {"text": "users", "size": 37}, {"text": "profile", "size": 36}, {"text": "subreddits", "size": 35}, {"text": "api", "size": 34}, {"text": "good", "size": 33}, {"text": "working", "size": 29}, {"text": "comment", "size": 28}, {"text": "time", "size": 25}, {"text": "trivia", "size": 25}, {"text": "page", "size": 25}, {"text": "post", "size": 24}, {"text": "list", "size": 24}, {"text": "user", "size": 23}, {"text": "topics", "size": 22}, {"text": "submissions", "size": 22}, {"text": "program", "size": 20}, {"text": "recent", "size": 20}, {"text": "access", "size": 20}, {"text": "app", "size": 20}, {"text": "great", "size": 19}, {"text": "top", "size": 18}, {"text": "snoopsnoo", "size": 18}, {"text": "check", "size": 18}, {"text": "lot", "size": 18}, {"text": "posted", "size": 18}, {"text": "feature", "size": 17}, {"text": "suggestions", "size": 17}, {"text": "topic", "size": 17}, {"text": "built", "size": 17}, {"text": "back", "size": 17}, {"text": "question", "size": 17}, {"text": "give", "size": 16}, {"text": "players", "size": 16}, {"text": "fun", "size": 16}, {"text": "add", "size": 16}, {"text": "love", "size": 15}, {"text": "multiplayer", "size": 15}, {"text": "show", "size": 15}, {"text": "server", "size": 15}, {"text": "fixed", "size": 15}, {"text": "adding", "size": 15}, {"text": "thought", "size": 15}, {"text": "days", "size": 14}, {"text": "subreddit", "size": 14}, {"text": "things", "size": 14}, {"text": "hear", "size": 14}, {"text": "change", "size": 14}, {"text": "number", "size": 14}, {"text": "due", "size": 14}, {"text": "work", "size": 13}, {"text": "make", "size": 13}, {"text": "people", "size": 13}, {"text": "interested", "size": 13}, {"text": "suggestion", "size": 13}, {"text": "public", "size": 13}, {"text": "sense", "size": 13}, {"text": "issue", "size": 13}, {"text": "play", "size": 13}, {"text": "understand", "size": 13}, {"text": "links", "size": 13}, {"text": "times", "size": 13}, {"text": "wrong", "size": 12}, {"text": "update", "size": 12}, {"text": "added", "size": 12}, {"text": "google", "size": 12}, {"text": "code", "size": 12}, {"text": "results", "size": 12}, {"text": "limited", "size": 11}, {"text": "games", "size": 11}, {"text": "shows", "size": 11}, {"text": "link", "size": 11}, {"text": "mobile", "size": 11}, {"text": "issues", "size": 11}, {"text": "makes", "size": 11}, {"text": "python", "size": 11}, {"text": "text", "size": 11}, {"text": "answer", "size": 10}, {"text": "points", "size": 10}, {"text": "hope", "size": 10}, {"text": "real", "size": 10}, {"text": "section", "size": 10}, {"text": "hard", "size": 10}, {"text": "ago", "size": 10}, {"text": "url", "size": 10}, {"text": "restrictions", "size": 10}, {"text": "ca", "size": 10}, {"text": "works", "size": 10}, {"text": "problem", "size": 10}, {"text": "end", "size": 9}, {"text": "fix", "size": 9}, {"text": "website", "size": 9}, {"text": "subs", "size": 9}, {"text": "incorrect", "size": 9}, {"text": "developer", "size": 9}, {"text": "couple", "size": 9}, {"text": "karma", "size": 9}, {"text": "charts", "size": 9}, {"text": "manually", "size": 9}, {"text": "web", "size": 9}, {"text": "sarcasm", "size": 8}, {"text": "improve", "size": 8}, {"text": "logic", "size": 8}, {"text": "launched", "size": 8}, {"text": "nlp", "size": 8}, {"text": "takes", "size": 8}, {"text": "sentences", "size": 8}, {"text": "gilded", "size": 8}, {"text": "process", "size": 8}, {"text": "mentioned", "size": 8}, {"text": "point", "size": 8}, {"text": "bug", "size": 8}, {"text": "made", "size": 8}, {"text": "luck", "size": 7}, {"text": "wanted", "size": 7}, {"text": "project", "size": 7}, {"text": "wo", "size": 7}, {"text": "suggested", "size": 7}, {"text": "interesting", "size": 7}, {"text": "thing", "size": 7}, {"text": "online", "size": 7}, {"text": "jokes", "size": 7}, {"text": "case", "size": 7}, {"text": "kind", "size": 7}, {"text": "pretty", "size": 7}, {"text": "recently", "size": 7}, {"text": "pm", "size": 7}, {"text": "bit", "size": 7}, {"text": "submission", "size": 7}, {"text": "submit", "size": 7}, {"text": "account", "size": 7}, {"text": "day", "size": 7}, {"text": "sources", "size": 7}, {"text": "dataset", "size": 7}, {"text": "apps", "size": 7}, {"text": "earlier", "size": 6}, {"text": "free", "size": 6}, {"text": "mvp", "size": 6}, {"text": "testing", "size": 6}, {"text": "analytics", "size": 6}, {"text": "parsing", "size": 6}, {"text": "happy", "size": 6}, {"text": "timezone", "size": 6}, {"text": "test", "size": 6}, {"text": "weird", "size": 6}, {"text": "tweak", "size": 6}, {"text": "released", "size": 6}, {"text": "js", "size": 6}, {"text": "thinks", "size": 6}, {"text": "lol", "size": 6}, {"text": "full", "size": 6}, {"text": "answers", "size": 6}, {"text": "search", "size": 6}, {"text": "thread", "size": 6}, {"text": "categorized", "size": 6}, {"text": "common", "size": 6}, {"text": "activity", "size": 6}, {"text": "moment", "size": 6}, {"text": "development", "size": 6}, {"text": "synopsis", "size": 6}, {"text": "source", "size": 6}, {"text": "popular", "size": 6}, {"text": "helps", "size": 6}, {"text": "username", "size": 6}, {"text": "girlfriend", "size": 6}, {"text": "requests", "size": 6}, {"text": "building", "size": 6}, {"text": "minutes", "size": 6}, {"text": "items", "size": 5}, {"text": "word", "size": 5}, {"text": "created", "size": 5}, {"text": "database", "size": 5}, {"text": "mind", "size": 5}, {"text": "talking", "size": 5}, {"text": "report", "size": 5}, {"text": "received", "size": 5}, {"text": "thoughts", "size": 5}, {"text": "automatically", "size": 5}, {"text": "trouble", "size": 5}, {"text": "sign", "size": 5}, {"text": "product", "size": 5}, {"text": "correct", "size": 5}, {"text": "threshold", "size": 5}, {"text": "hey", "size": 5}, {"text": "default", "size": 5}, {"text": "month", "size": 5}, {"text": "version", "size": 5}, {"text": "analyzing", "size": 5}, {"text": "information", "size": 5}, {"text": "refresh", "size": 5}, {"text": "put", "size": 5}, {"text": "guess", "size": 5}], "recent_posts": [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 6, 3, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 3, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 3, 0, 1, 0, 2, 1, 1, 0, 0, 0, 0], "subreddit": {"name": "All", "children": [{"name": "Other", "children": [{"submission_karma": 0, "name": "A_irsoft", "posts": 3, "comments": 3, "comment_karma": 11, "karma": 11, "submissions": 0}, {"submission_karma": 23, "name": "SnoopSnoo", "posts": 29, "comments": 22, "comment_karma": 35, "karma": 58, "submissions": 7}, {"submission_karma": 0, "name": "Trivius", "posts": 1, "comments": 1, "comment_karma": 2, "karma": 2, "submissions": 0}, {"submission_karma": 0, "name": "WastelandPowers", "posts": 3, "comments": 3, "comment_karma": 4, "karma": 4, "submissions": 0}, {"submission_karma": 0, "name": "daily3me", "posts": 4, "comments": 4, "comment_karma": 5, "karma": 5, "submissions": 0}, {"submission_karma": 0, "name": "mydaily3_sandbox", "posts": 3, "comments": 2, "comment_karma": 2, "karma": 2, "submissions": 1}, {"submission_karma": 9, "name": "snoovatars", "posts": 5, "comments": 4, "comment_karma": 5, "karma": 14, "submissions": 1}, {"submission_karma": 0, "name": "trollabot", "posts": 1, "comments": 1, "comment_karma": 2, "karma": 2, "submissions": 0}]}, {"name": "General", "children": [{"submission_karma": 0, "name": "AdviceAnimals", "posts": 6, "comments": 6, "comment_karma": 51, "karma": 51, "submissions": 0}, {"submission_karma": 0, "name": "AskReddit", "posts": 8, "comments": 8, "comment_karma": 18, "karma": 18, "submissions": 0}, {"submission_karma": 0, "name": "CasualConversation", "posts": 2, "comments": 2, "comment_karma": 4, "karma": 4, "submissions": 0}, {"submission_karma": 0, "name": "EVEX", "posts": 5, "comments": 5, "comment_karma": 8, "karma": 8, "submissions": 0}, {"submission_karma": 0, "name": "NoStupidQuestions", "posts": 1, "comments": 1, "comment_karma": 8, "karma": 8, "submissions": 0}, {"submission_karma": 0, "name": "Showerthoughts", "posts": 1, "comments": 1, "comment_karma": 1, "karma": 1, "submissions": 0}, {"submission_karma": 0, "name": "funny", "posts": 3, "comments": 3, "comment_karma": 16, "karma": 16, "submissions": 0}, {"submission_karma": 0, "name": "mildlyinteresting", "posts": 1, "comments": 1, "comment_karma": 5, "karma": 5, "submissions": 0}, {"submission_karma": 0, "name": "misc", "posts": 6, "comments": 6, "comment_karma": 16, "karma": 16, "submissions": 0}, {"submission_karma": 0, "name": "pics", "posts": 2, "comments": 2, "comment_karma": 4, "karma": 4, "submissions": 0}, {"submission_karma": 0, "name": "tipofmytongue", "posts": 9, "comments": 9, "comment_karma": 28, "karma": 28, "submissions": 0}, {"submission_karma": 0, "name": "videos", "posts": 2, "comments": 2, "comment_karma": 9, "karma": 9, "submissions": 0}]}, {"name": "Technology", "children": [{"submission_karma": 0, "name": "AppEngine", "posts": 2, "comments": 2, "comment_karma": 4, "karma": 4, "submissions": 0}, {"submission_karma": 291, "name": "InternetIsBeautiful", "posts": 127, "comments": 126, "comment_karma": 365, "karma": 656, "submissions": 1}, {"submission_karma": 14, "name": "Python", "posts": 7, "comments": 6, "comment_karma": 11, "karma": 25, "submissions": 1}, {"submission_karma": 0, "name": "UsefulWebsites", "posts": 2, "comments": 2, "comment_karma": 10, "karma": 10, "submissions": 0}, {"submission_karma": 11, "name": "chrome", "posts": 2, "comments": 1, "comment_karma": 1, "karma": 12, "submissions": 1}, {"submission_karma": 557, "name": "dataisbeautiful", "posts": 37, "comments": 34, "comment_karma": 155, "karma": 712, "submissions": 3}, {"submission_karma": 9, "name": "golang", "posts": 8, "comments": 7, "comment_karma": 10, "karma": 19, "submissions": 1}, {"submission_karma": 23, "name": "learnpython", "posts": 21, "comments": 20, "comment_karma": 28, "karma": 51, "submissions": 1}, {"submission_karma": 0, "name": "programming", "posts": 3, "comments": 3, "comment_karma": 4, "karma": 4, "submissions": 0}]}, {"name": "Business", "children": [{"submission_karma": 0, "name": "Entrepreneur", "posts": 9, "comments": 9, "comment_karma": 24, "karma": 24, "submissions": 0}, {"submission_karma": 3, "name": "roastmystartup", "posts": 5, "comments": 4, "comment_karma": 5, "karma": 8, "submissions": 1}, {"submission_karma": 21, "name": "startups", "posts": 22, "comments": 20, "comment_karma": 27, "karma": 48, "submissions": 2}, {"submission_karma": 4, "name": "SideProject", "posts": 1, "comments": 0, "comment_karma": 0, "karma": 4, "submissions": 1}]}, {"name": "Gaming", "children": [{"submission_karma": 0, "name": "IndieGaming", "posts": 1, "comments": 1, "comment_karma": 1, "karma": 1, "submissions": 0}, {"submission_karma": 0, "name": "KerbalSpaceProgram", "posts": 2, "comments": 2, "comment_karma": 2, "karma": 2, "submissions": 0}, {"submission_karma": 0, "name": "WebGames", "posts": 23, "comments": 23, "comment_karma": 60, "karma": 60, "submissions": 0}, {"submission_karma": 1, "name": "DestinyTheGame", "posts": 1, "comments": 0, "comment_karma": 0, "karma": 1, "submissions": 1}]}, {"name": "Lifestyle", "children": [{"submission_karma": 0, "name": "Mydaily3", "posts": 7, "comments": 7, "comment_karma": 14, "karma": 14, "submissions": 0}, {"submission_karma": 0, "name": "Wishlist", "posts": 3, "comments": 3, "comment_karma": 5, "karma": 5, "submissions": 0}, {"submission_karma": 0, "name": "childfree", "posts": 6, "comments": 6, "comment_karma": 14, "karma": 14, "submissions": 0}, {"submission_karma": 482, "name": "secretsanta", "posts": 33, "comments": 32, "comment_karma": 172, "karma": 654, "submissions": 1}, {"submission_karma": 1, "name": "Favors", "posts": 1, "comments": 0, "comment_karma": 0, "karma": 1, "submissions": 1}]}, {"name": "Meta", "children": [{"submission_karma": 0, "name": "SubredditDrama", "posts": 11, "comments": 11, "comment_karma": 58, "karma": 58, "submissions": 0}, {"submission_karma": 170, "name": "TheoryOfReddit", "posts": 10, "comments": 9, "comment_karma": 56, "karma": 226, "submissions": 1}, {"submission_karma": 0, "name": "redditdev", "posts": 3, "comments": 3, "comment_karma": 3, "karma": 3, "submissions": 0}]}, {"name": "News and Politics", "children": [{"submission_karma": 0, "name": "conspiracy", "posts": 3, "comments": 3, "comment_karma": 11, "karma": 11, "submissions": 0}, {"submission_karma": 0, "name": "worldnews", "posts": 2, "comments": 2, "comment_karma": 2, "karma": 2, "submissions": 0}]}, {"name": "Sports", "children": [{"submission_karma": 0, "name": "devils", "posts": 1, "comments": 1, "comment_karma": 4, "karma": 4, "submissions": 0}]}, {"name": "Entertainment", "children": [{"submission_karma": 179, "name": "harrypotter", "posts": 3, "comments": 2, "comment_karma": 8, "karma": 187, "submissions": 1}, {"submission_karma": 0, "name": "homestuck", "posts": 2, "comments": 2, "comment_karma": 3, "karma": 3, "submissions": 0}, {"submission_karma": 15, "name": "psych", "posts": 3, "comments": 2, "comment_karma": 7, "karma": 22, "submissions": 1}, {"submission_karma": 12, "name": "seinfeld", "posts": 2, "comments": 1, "comment_karma": 3, "karma": 15, "submissions": 1}, {"submission_karma": 7, "name": "blackmirror", "posts": 1, "comments": 0, "comment_karma": 0, "karma": 7, "submissions": 1}]}, {"name": "Locations", "children": [{"submission_karma": 0, "name": "singapore", "posts": 1, "comments": 1, "comment_karma": 4, "karma": 4, "submissions": 0}]}]}}, "synopsis": {"television": {"data": [{"count": 3, "value": "psych"}]}, "lifestyle": {"data": [{"count": 36, "value": "gifts and charity"}, {"count": 7, "value": "self-help and motivation"}, {"count": 6, "value": "relationships"}]}, "possessions": {"data_extra": [{"count": 12, "sources": ["http://www.reddit.com/r/funny/comments/3gd7to/_/ctx75ih", "http://www.reddit.com/r/worldnews/comments/3f4m58/_/ctlmqiw", "http://www.reddit.com/r/CasualConversation/comments/3e27kr/_/ctb0tp5", "http://www.reddit.com/r/InternetIsBeautiful/comments/33fepc/_/cqklhaq", "http://www.reddit.com/r/InternetIsBeautiful/comments/2wstiw/_/cou9xe1", "http://www.reddit.com/r/InternetIsBeautiful/comments/2wstiw/_/cou9jg5", "http://www.reddit.com/r/childfree/comments/2r6dte/_/cnd9et5", "http://www.reddit.com/r/KerbalSpaceProgram/comments/2r6lnb/_/cnd8nwr", "http://www.reddit.com/r/devils/comments/2r4yeq/_/cncu0bm", "http://www.reddit.com/r/dataisbeautiful/comments/2r3jnk/_/cncpb2j", "http://www.reddit.com/r/misc/comments/2qzz64/_/cnbzple", "http://www.reddit.com/r/programming/comments/2qx5ij/_/cnbx5yq"], "value": "site"}, {"count": 11, "sources": ["http://www.reddit.com/r/InternetIsBeautiful/comments/33fepc/_/cqkjp9g", "http://www.reddit.com/r/AdviceAnimals/comments/30hxhr/_/cpt4b4l", "http://www.reddit.com/r/InternetIsBeautiful/comments/2wstiw/_/couatb9", "http://www.reddit.com/r/WastelandPowers/comments/2sqj2b/_/cns3sl8", "http://www.reddit.com/r/secretsanta/comments/2r7xhr/_/cndz6gm", "http://www.reddit.com/r/secretsanta/comments/2r7xhr/_/cndsv7a", "http://www.reddit.com/r/dataisbeautiful/comments/2r3jnk/_/cncwrxu", "http://www.reddit.com/r/devils/comments/2r4yeq/_/cncu0bm", "http://www.reddit.com/r/dataisbeautiful/comments/2r3jnk/_/cncqjm7", "http://www.reddit.com/r/InternetIsBeautiful/comments/2qucap/_/cna4yzr", "http://www.reddit.com/r/InternetIsBeautiful/comments/2qucap/_/cn9urem"], "value": "program"}, {"count": 3, "sources": ["http://www.reddit.com/r/tipofmytongue/comments/31jydx/_/cq2iw1r", "http://www.reddit.com/r/pics/comments/2zqz1x/_/cplr132", "http://www.reddit.com/r/InternetIsBeautiful/comments/2qucap/_/cnl181a"], "value": "algorithm"}, {"count": 3, "sources": ["http://www.reddit.com/r/dataisbeautiful/comments/2r3jnk/_/cnc3vzb", "http://www.reddit.com/r/misc/comments/2qzz64/_/cnbftn1", "http://www.reddit.com/r/startups/comments/3l2ziv/any_recommendations_for_a_branded_url_shortener/"], "value": "server"}, {"count": 2, "sources": ["http://www.reddit.com/r/SnoopSnoo/comments/3uv7kc/_/cxjmen6", "http://www.reddit.com/r/dataisbeautiful/comments/2r3jnk/_/cncrw9b"], "value": "code"}, {"count": 2, "sources": ["http://www.reddit.com/r/dataisbeautiful/comments/2r3jnk/_/cnc3vzb", "http://www.reddit.com/r/InternetIsBeautiful/comments/2qucap/_/cn9kusm"], "value": "time"}, {"count": 1, "sources": ["http://www.reddit.com/r/SnoopSnoo/comments/3yp4n8/_/cyfhqw7"], "value": "cc"}, {"count": 1, "sources": ["http://www.reddit.com/r/WebGames/comments/3n26s2/_/cvkbc3h"], "value": "testing"}, {"count": 1, "sources": ["http://www.reddit.com/r/tipofmytongue/comments/31jydx/_/cq2j7sa"], "value": "seo"}, {"count": 1, "sources": ["http://www.reddit.com/r/tipofmytongue/comments/31jydx/_/cq2iw1r"], "value": "site rubbish"}, {"count": 1, "sources": ["http://www.reddit.com/r/A_irsoft/comments/2r94l2/_/cndt8e4"], "value": "logic"}, {"count": 1, "sources": ["http://www.reddit.com/r/startups/comments/3l2ziv/any_recommendations_for_a_branded_url_shortener/"], "value": "custom domain"}, {"count": 1, "sources": ["http://www.reddit.com/r/programming/comments/2qx5ij/_/cnau2bp"], "value": "intention"}, {"count": 1, "sources": ["http://www.reddit.com/r/seinfeld/comments/3r8mu3/_/cwlu45z"], "value": "friend"}, {"count": 1, "sources": ["http://www.reddit.com/r/EVEX/comments/2ztguf/_/cpqa7b1"], "value": "process"}, {"count": 1, "sources": ["http://www.reddit.com/r/chrome/comments/323000/chrome_on_os_x_yosemite_search_with_google/"], "value": "default web browser"}, {"count": 1, "sources": ["http://www.reddit.com/r/EVEX/comments/2ztguf/_/cpr5v4c"], "value": "data visualization skill"}, {"count": 1, "sources": ["http://www.reddit.com/r/startups/comments/3k3cas/_/cuuhasa"], "value": "post"}, {"count": 1, "sources": ["http://www.reddit.com/r/Python/comments/3l1x4x/_/cv6fzs0"], "value": "response"}, {"count": 1, "sources": ["http://www.reddit.com/r/InternetIsBeautiful/comments/2qucap/_/cnan89z"], "value": "sarcasm detector"}, {"count": 1, "sources": ["http://www.reddit.com/r/startups/comments/3l2ziv/any_recommendations_for_a_branded_url_shortener/"], "value": "url"}, {"count": 1, "sources": ["http://www.reddit.com/r/InternetIsBeautiful/comments/2qucap/_/cnbvmwb"], "value": "list"}, {"count": 1, "sources": ["http://www.reddit.com/r/learnpython/comments/3kfrii/_/cux9m25"], "value": "connection"}, {"count": 1, "sources": ["http://www.reddit.com/r/EVEX/comments/2ztguf/_/cpqa7b1"], "value": "seed data"}]}, "business": {"data": [{"count": 36, "value": "entrepreneurship"}]}, "books": {"data": [{"count": 3, "value": "harry potter"}]}, "favorites": {"data": [{"count": 1, "sources": ["http://www.reddit.com/r/misc/comments/2qzz64/_/cnbbvee"], "value": "redditinvestigator"}, {"count": 1, "sources": ["http://www.reddit.com/r/EVEX/comments/2ztguf/_/cpr5v4c"], "value": "web development"}]}, "attributes": {"data_extra": [{"count": 3, "sources": ["http://www.reddit.com/r/dataisbeautiful/comments/2r3jnk/_/cndz0f9", "http://www.reddit.com/r/secretsanta/comments/2r7xhr/_/cndvgvo", "http://www.reddit.com/r/dataisbeautiful/comments/2r3jnk/_/cncm7l7"], "value": "testing feature"}], "data": [{"count": 3, "sources": ["http://www.reddit.com/r/UsefulWebsites/comments/328vgb/_/cq9edg0", "http://www.reddit.com/r/InternetIsBeautiful/comments/2wstiw/_/cou7p6f", "http://www.reddit.com/r/programming/comments/2qx5ij/_/cnaueqc"], "value": "developer of this site"}, {"count": 2, "sources": ["http://www.reddit.com/r/conspiracy/comments/325hb3/_/cq881b8", "http://www.reddit.com/r/singapore/comments/30n2ac/_/cpuccv2"], "value": "developer of snoopsnoo"}, {"count": 1, "sources": ["http://www.reddit.com/r/EVEX/comments/2ztguf/_/cpmnuhs"], "value": "creator of the site"}, {"count": 1, "sources": ["http://www.reddit.com/r/snoovatars/comments/2xr0dy/i_created_an_api_to_get_your_snoovatar_as_a_png/"], "value": "creator"}]}, "technology": {"data": [{"count": 127, "value": "internet"}, {"count": 37, "value": "data visualization"}, {"count": 28, "value": "python"}, {"count": 11, "value": "programming"}]}}, "version": 8, "metadata": {"latest_submission_id": "4263aj", "latest_comment_id": "d0bb25n", "reddit_id": "hc427"}}
	Processing complete... 0:00:06.084066


License
=======
MIT License