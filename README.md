# This project
A simple and reusable ads.txt file that claims that per the ads.txt format spec v1.1 that advertisers must directly accept that no ads are sold on the website.

That's it.

# What?
Billions of dollars is flowing around the web in the form of advertising.  Every domain can display ads; but have you stopped to think about how every web domain tells others what, and who, is allowed by them?

That is what this ads.txt file is. What you are looking at is really a standard file used by many advertisers to declare on each website what is allowed, who is allowed to resell, etc. So this projects exists to simply be a simple "copy and paste" solution that can be imported into other projects or reused to simply declare that the website handles its own buisness and nobody else has authority over ads.

# Why?
I feel attacked by ads. I wanted to say "I do not consent to your bullshit and fruad." in their own language... so I needed this for my own websites. I then found myself copying and pasting it around to a few of my websites because its basicly a finished product now that I have a single file I created that fits this need after reading the spec and diving into the file format used by advertisers in this space.  The good news is you dont have to do any of that. That can all stay out of your head, if you dont want it in your head. But its in mine now, and so my suffering is your gain.

Also, an empty file can be ambiguous... so this also closes a possible security issue where unlimited spend could be assumed in the worst case according to old versions of the spec.

# How?
Just deploy the ads.txt from this repositiory into the web root (aka "/") of the domamin or sub-domain you want to give the finger to ad sellers on.
