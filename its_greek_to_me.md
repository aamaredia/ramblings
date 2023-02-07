# It’s Greek to Me
Some musings on providing technical support to engineers using the Socratic method. A personal favorite style of mine that I’ve used a lot over the years. I’ve found a lot of success using the Socratic method in my teachings and I’m hoping this article helps engineers move from just providing help to being better teachers.

_Quick note_: I’m far from an educational expert, have done very few readings on this subject, and experimented with a sample size that would not meet any scientific rigor. I really don’t find this unique or novel either, but wanted to jot down an idea to start a conversation on some learning techniques engineers are using. So feel free to share with me what’s worked for ya. Or what hasn’t.

## Helping Engineers vs. Teaching Engineers
So let’s draw a line first; there’s a difference between providing help and teaching. Put as fortune cookie philosophy, help is fishing; we want to teach how to fish. What’s fishing look like for engineers? Something like this:

> Junior Engineer: “Hey, my code keep crashing here, I’m not sure what to do”
> 
> _Senior Engineer looks at code_
> 
> _Senior Engineer types something and runs code_
> 
> _It works._
> 
> Senior Engineer: “There ya go” 
> 
> _Senior Engineer swivels around and continues putting the finishing touches on a new OS they started working on this morning_

We’ve all been here – on both sides of the conversation, but more often than not, we want our engineers fishing for themselves. This doesn’t always mean providing the solution right away, it means teaching them to think, work through problems, ask the right questions. For me, this has always been something that I’ve been looking to improve on. I’ve realized this takes time, effort, sometimes battles of patience – something an already taxed engineer doesn’t want to hear. But the more you invest, the more you’ll get out. As for me, I learned how to invest into that where everyone else learns things these days – the internet.

## Internet Inspiration
So long, long ago, on an internet far far away, I came across this beautiful post from [Rick Garikov on teaching binary arithmetic to third graders using the Socratic method](http://www.garlikov.com/Soc_Meth.html). Definitely give the article a read as his thought process through the lesson is great, but the summary is this – Rick teaches third graders binary arithmetic by driving the group with only poignant questions allowing them to logically work from a base 10 number system to a base 2 number system. He also provides his own takeaways from the exercise, which will become relevant in our discussion as we go along.

So yeah, after reading this article, I realized at the time I had two things: a handful of interns/junior engineers that would make the perfect guinea pigs and a bit too much zeal in trying out social experiments on unsuspecting victims. I figured – if you can do this with third graders, let’s see how it works on professional engineers. And so began a few years of my own experimentation (or torture depending on your perspective). 

The next chance I got, I decided to teach by only asking questions. I’ll say it was a bit of a rough go at first, but shortcutting to the present, I actually found a lot of success with the process. I don’t implement as rigorous of a style as Rick demonstrates – but use it more as a guideline which is what’s presented to you reader to take and try to implement. So what did I end up implementing?

## Resist Statements
In practice, implementing this really comes down to a simple task: stating the obvious, we’re looking to resist providing answers or statements and instead start asking questions. More specifically, questions that will guide the engineer in the direction they should go. 

This sounds simple, but it is much easier said than done. Especially early on, you’ll struggle to find the right question to ask or be fighting the urge to give something away that to you feels so simple that it’s persistently on the edge of your tongue fighting to fly the words out. So let’s go back to Junior.

> Junior Engineer: “Hey my code keeps crashing here, I’m not sure what to do”

What’s some questions we can ask here? (Yes I’m hitting you with socratic questions). Feel free to think a bit, but here’s some questions I lean on time and time again.

> Senior Engineer: “That’s cool, what have ya tried?” “What do ya think the issue is?” “What do you know? What do you not know?” “What would help you?”

Our example is trivial, but you’ll find that more often than not you can find a good question to ask of Junior. There’s a types of questions I typically reach for that you can use as a guideline:

1. Clarify their thinking – “Why do you think that?”
2. Challenge assumptions – “Does that always work?”
3. Question the evidence – “How does that prove we can do that?”
4. Seek alternatives – “What’s another way to do this? Why’s this the best way?”
5. Test implications and consequences – “If I changed this, then what happens?”
6. Meta questioning – “Does me asking that last question give you a hint?”

This isn’t to say you should stop statements entirely or give answers, but try to minimize it – or have that come from Junior. 

## Shifting Ownership
In our example, we’re making a dynamic shift by moving the ownership of the problem from the mentor to the mentee. More so, keeping it with the mentee. The metaphorical car isn’t being driven by the senior engineer, the junior engineer is driving it. The onus is on them to find the solution by working through our questions.

Again, what would you ask if Junior came back with this?

> Junior Engineer: “Something about this model just isn’t working. I have this code, but I get this error”

Maybe something like:

> Senior Engineer: “What does this model do?” “What are you trying to change” “What’s a model?” “What led you to make the changes here?” “Can you explain to me how this code fits into the application”? “What do you think the relationship between this code and the database is?” “Say I changed this field to this, how would the database change? And the API? And the frontend?”

You may find it hard to keep the ball in their court, but try to persist. You’ll also notice in the example above that the more specific the problem gets, the more specific your questions can get, but also the more directions you can lead your engineers. So what do you do?

## Gotta stay ahead
Our metaphorical car is really a rally car with you in the passenger seat. I say rally car cause this is going to move fast even with you taking time to think, but you have to think ahead. You’ll want to stay ahead of your engineers, likely figuring out the solution before your engineers all so you can ask the _right_ questions that will lead your engineers in the _right_ direction. How far ahead? That’s up to you. Most often, I’m just one question ahead. Occasionally you know the answer, which gives you a sort of guiding light to work towards.

To be perfectly frank, you’ll eventually set the wrong direction, but that’s okay! It’s okay to go in the wrong direction. Why? Cause that’s how you’re thinking or reading the signs which in turn teaches engineers to read the signs the same way. You’ll find some new information which then corrects you back on course, but that’s part of the process. The goal is to impart the thought process, not the answers.

> Senior Engineer: “Yeah, have you tried looking at the other arguments on the field?”
> 
> Junior Engineer: “I think so, I turned X on and off, toggled Y, and did every combination of X, Y, and Z”
> 
> Senior Engineer: “Ah cool, I was thinking it might be something else, but that rules out so and so, what do you know about . . .”

## Being Practical
This all sounds great, but it just seems exhausting. Rick calls this out in his article – it takes a lot of time and a lot of concentration. So be pragmatic. You don’t need to be the Riddler. Let’s go back to Junior:

> Junior Engineer: “Something about this model just isn’t working. I have this code, but I get this error”
> 
> Senior Engineer: “Cool lemme explain what this model does, then after that, let me know how that helps you”

It’s cool to just cut some things out, like the example above illustrates. But, try to keep the ownership out of your hands and always be guiding the engineer towards the direction you want them to go.

## Tips and Tricks
There’s really not much more to it than that. Be patient, not just with others, but yourself. You’ll find that it seems rough at first, you’ll feel lost, but over time you’ll find a flow to things. But just to help, here’s some more tips and tricks I’ve implemented over the years.

<ins>Gather Information Upfront</ins> – Like with most problems, ask as many obvious questions as you can upfront so you can understand the problem thoroughly. The better you understand things, the better help you can give

<ins>Test Assumptions</ins> – More often not, you’ll find that the obvious isn’t so obvious. Or, in reality, the thing you assume your engineer knows is pretty shaky. So, test their knowledge; see if they know what they need to know. If not…

<ins>Give Homework</ins> – Yes, be a professor. It’s okay to send your engineers back with some homework to do. Sometimes it’s having them read some different code, or reading documentation, or an article, or having them think about something then coming back with an answer. You’ll both be more efficient if you don’t spend this entire process glued together in front of a screen.

<ins>Reject Broad Questions</ins> – This is something I tell engineers on Day 1, but I reject very broad questions. Ask them to give you something more specific. “Something isn’t working” is too broad; force them to be more specific. I’ve very up front about this – “you’ve gotta be more specific than that” We usually ask engineers to ask the most specific question they can – “So I’m working on making this change, I’ve tried X, Y, and Z, but I can’t seem to get the foo field to show up on this bar model. Do you think I need to do this by making this change or that change?”

<ins>The Lifeline</ins> – I always warn my engineers about my Socratic approach beforehand. At the same time, I always offer them a free out. It’s usually something like this: “If you’re ever frustrated with this, or really just need an answer cause you know that’s all you need, you’ve always got a free out. Just say ‘alright, just tell me this’ and I’ll give it to you.” Giving your developers a lifeline really helps them manage their state in all this.

<ins>The Secret Phrase</ins> – When turning away developers or forcing them to learn to fish or right when they’re getting disheartened, I have a recurring phrase that I like to use: “I don’t want to steal away the eureka moment from you by just telling you the solution. You’re almost there! Now tell me how…” Seriously, it’s terrible to say, but it’s magic. It reassures developers that they have the ability to overcome the hurdle while also giving them something to work towards. And when they hit that moment, you’ll be celebrating too.

## Pitfalls
As I mentioned earlier, this technique takes time and effort. Sometimes it’s late in the day, or you’ve got a deadline, or Junior’s just bugged you 8 times in the last 2 hours and it’s just easier to go Thanos by doing it yourself. And to be perfectly honest, this is totally cool. Sometimes, the best way to teach is just to provide them with fish. The two examples that come to mind are IT issues or tribal knowledge that no one can deduce.

I don’t see the technique I highlight as a one size fits all. As a wise mentor once told me, if you have 5 engineers, you will have to develop 5 different ways to teach them. Do not make the fallacy that this should be used ubiquitously; rather it should be crafted. I tend to lean on this method for the most junior of engineers – interns/co-ops, first year engineers. Not to say I haven’t done this with senior engineers. In particular, this is a fun method to use when working with designs with seasoned engineers. Generally, I’ve used this with more junior engineers because they’re not crunched for timelines and you tend to have more time to work with them.

## Benefits and Final Thoughts
The biggest win I’ve gotten from this approach is training developers how to approach problems. We don’t want engineers to rely on pattern recognition or be a conditional statement (if this then do that); we want to teach them to think critically. This methodology really helps engineers actively work through all the parts of a problem that you do and learn through that. So when you’re looking for information, pushing in a direction you go, pulling from your knowledge banks, then the engineer is forced to work through the same process. To me, this guided practice is incredibly valuable.

Do remember teaching is a personal craft that is developed. You have to mold it to your own style. We all have different strengths, weaknesses, ways of learning, etc. The same applies to your engineers. Take this as a narrative of one of my approaches to teaching to craft your own personal style.

In the future, I hope to include an example of one of these sessions with an engineer in the same style Rick did with his class.
