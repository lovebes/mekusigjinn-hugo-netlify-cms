---
title: "Elixir: I learned it"
date: 2020-12-02T17:59:45.955Z
description: My experience in learning this wonderful language called Elixir.
---
I first started with the <https://elixir-lang.org/getting-started/introduction.html> guide - really it's super packed with information. Really do not skip this part even though it's dry. It goes over literally EVERYTHING. I also did their OTP guide too - they really go over everything in terms of the depth of what you'll need when you start developing with Elixir. I'm doing my own project now and I still haven't even touched the section on inter-node computing! This paved the backbone of my study.

Then I practiced Elixir language itself doing some small - medium challenges over at <https://exercism.io/tracks/elixir> to understand data parsing. I skipped the algorithm challenge-styles because .. I'm not prepping for an interview :) But I did do the recursion stuff because it's the heart of Elixir for for-loops.

I've yet to come across where I had to inherent use a recursion though, when I started doing my own project. More on that below.

Then, I started reading Elixir in Action (<https://www.manning.com/books/elixir-in-action>). This guy has a Youtube video (<https://www.youtube.com/watch?v=JvBT4XBdoUE>) that really made everything click, and made me jump into Elixir. Now I didn't read in detail - after a certain point in time reading PDF files really doesn't work for me. I skipping the parts I came familiar with, and he had some standards-based approach on how to use piping / design functions to be used for piping that was useful so I read that part.. rest of the stuff I already know because of the Elixir.lang guide.

After that I wanted to know more about OTP, and I came across this awesome two-part blog post: <https://akoutmos.com/post/actor-model-genserver-app/>, <https://akoutmos.com/post/actor-model-genserver-app-two/>) - this laid the foundation on how to use OTP/GenServer to create a cache-based, DB-backed layer! It's so simple and elegant than anything I've ever accomplished on Golang/Redis...

After that I read the Phoenix Guide (<https://hexdocs.pm/phoenix/overview.html>), and followed through with creating a Phoenix app. Between the blog post and this guide, that was more than enough background knowledge for me to start my own project.

My own project had to have something related to Ecto, of course some frontend (no JS as possible), and of course LiveView. So I'm creating something that does that, and hopefully soon I'll be able to expand on the project to do the cooler parts of Phoenix - like LiveView, Channels, Presence. Also hopefully soon I'll play around with erlPort for Python, video framework called Membrane, and IoT stack called Nerves.

Building stuff is fun! and I think makes me learn wayyy faster. Like forcing myself to write tests (super annoying) realized holy crap Elixir tests are freaggin faster than any React tests. Way more (is that even possible?) developer friendly than vanilla Golang tests. I worked at a Golang shop and no one wrote tests more than me - basically what the concensus was it was hard to simulate DB when doing Golang tests. Even though I tried to show you can do it with interfaces.. my efforts didn't make a dent. This comes included in Phoenix. Elixir's ExUnit library with Ecto.Sandbox is ... amazing. Truly amazing. But yeah in my short professional life, Elixir unit test is the BEST UNIT TESTING EXPERIENCE EVERRRRR. Next is React/testing-library. Then Golang. 

While doing that.. At the same time I'm currently, realllly slowly reading Programming Elixir 1.6 (<https://pragprog.com/titles/elixir16/programming-elixir-1-6/>) but again.. I suck at going through books. I am planning to read most of it because I am not good with parsing HTML code and I really want to be good and scraping / processing. Making a project is more fun! But I do come across standards, best practices, idiomatic ways to solve problems - which I hope Programming Elixir 1.6 book will help me.

Any questions I have that StackOverflow doesn't answer I try to ask in <https://elixirforum.com/>.

Whew man I guess I did read a lot in the last 3 months! But yeah I only did couple hours every day because I'm working. So I wasn't really efficient in my time. Plus.. until I knew enough to start creating my Phoenix project it was so slow and boring.