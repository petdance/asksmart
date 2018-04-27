Sometimes you need help with a computer problem.  Maybe it's how
to use a piece of software, or you can't figure out why your hardware
is acting flaky.  You want to ask for help, and that's good.  The
Internet is a great resource for getting help from your fellow
humans.

But you should put some thought into how to ask.  You'll increase
your chances of getting help, you'll get help faster, and you'll
get better help.

# Do your research first

The very fastest way to get the answer you seek is probably to find
it on the Web yourself.

Chances are, you're not the first person to have this problem.
Chances are, someone else has had this exact problem and it's been
posted somewhere on the Web.

The easiest way to find the answer to the question you want is just
to type the question directly into Google.  Maybe you're wondering
"I heard someone mention that you could do it, so I wonder how can
I get my git repository status in my shell prompt?"  So go to Google
and type in "how can I get my git repository status in my bash
prompt?"  Just like that.  And now you have a
[page of possible answers][git-shell].


Maybe all those pages don't apply to you, because they're mostly
about zsh and you're using bash, so change "shell" to "bash" and
[try it again][git-bash].  Now you've narrowed your search and you
have ten excellent sources of help.

[git-shell]: https://www.google.com/search?q=how+can+I+get+my+git+repository+status+in+my+shell+prompt%3F
[git-bash]: https://www.google.com/search?q=how+can+I+get+my+git+repository+status+in+my+bash+prompt%3F

In half a minute, you've found the answer you need, and it's more
complete than someone making an *ad hoc* answer on a mailing list
or in IRC.

## Use more words when searching

The more words you throw at Google, the better its answers come
back.  Don't worry about trying to whittle it down to only the most
important keywords, like "git status bash prompt".  Use full
sentences!  Asking a question in your search makes it more likely
you'll find a page with someone asking that question.

XXX Paste the warning message.

java.lang.Thread.run(Thread.java:679) Caused by: org.apache.solr.common.SolrException: Error loading class 'solr.VelocityResponseWriter' at 

# Look in specialized places

## Stack Overflow

## SuperUser

## ServerFault

# Be respectful

Do keep in mind that the people from whom you want help are usually not paid to help you, but are instead helping you out of altruism, goodwill, or a desire to build community for their technology.  None of those things means they will put up with abuse, nagging, or profanity.

One particular type of disrespect is common and will often result in you getting abused or banned from the forum: "negging", or demanding help based on belittling the technology you want help from.  For example, if you join a Python chat channel and demand help because Python does something poorly that Java does well, it is more likely to get you kicked out than an answer.  For that matter, bad-mouthing competing technologies to make people in the forum "like" you doesn't work either.

# Ask as few people as possible

# Ask in the right place

# Explain the whole problem

Often the reason why you can't find an answer to your specific blocker is because you're actually using the wrong tool, command, or module for the task you want to accomplish.  This means that you should always explain what your overall goal is, because often responders can explain a more appropriate tool or command for you to use.  Example:

OK Request:

> Hello, I'm getting this error when I run json_parse on a file: [link to paste].  What could be causing that?

Better request:

> Hello, I'm trying to write a tool to parse the Github events stream.  After I unzip the bundles of JSON files, I get this error when I try to parse the first one with json_parse [link to paste].  Any ideas? 

In the second case, you've provided an opportunity for a responder who is familiar with the Github events stream to share specific knowledge (like that the file has a non-JSON header which needs to be stripped off), which may eliminate an entire quest for syntax errors.

# Be specific in stating the problem

Don't say "it doesn't work".  Explain the way in which it doesn't work.  Do you get no output?  Incorrect output?  If it's incorrect, what makes it incorrect, and what would the correct output be?  Don't expect that the reader knows what "working" means for you.  Where possible, provide a paste of any error output, as the specific error message is often helpful to those trying to diagnore your problem.  Supplying specific versions and library names is often also helpful, at least for the components that directly touch your problem.

# Be polite

# Assume that the problem is you

# Don't make it the reader's problem

# Explain what you've tried

# Give error messages

Always cut & paste entire error messages.  Don't paraphase: "It said it was out of space."  Paste the entire message, not just an identifier: "I got a XYZZY error."

# Write clearly

Avoid vague terms.  Avoid pronouns when possible, especially "it", which could mean many things when describing two or more entities interacting.

# Report back what you found

You owe it to the blogosphere and those who come after to explain
how you solved your problem.

# Scraps

* Don't tell us you're desperate.

* Don't tell us it's simple.

* Don't pretend to know more than you do.

* Don't apologize for not knowing.

* Tell us what you've tried.

* Tell us what you've diagnosed.

* Don't ask to ask.

* Don't ask about "most efficient".  There are many different types of efficiency.  If you mean "will execute fastest", then say that.  If you mean "easiest for me to code", then say that.
