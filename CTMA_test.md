
**CTMA Registration & Usage Testing Notes**


# Summary:  Places that felt "sticky"

Per Jon's request to call this information out, here's a list of places in the process that felt like they got (or were prone to get) me "stuck".  (Below this section are more details and stream-of-thought notes that pertain to each; these are linked for ease of navigation because this turned into a novella.)

I will be testing the application itself more over the weekend, so so far these notes only cover the registration process. 



* **[After clicking "Getting Started"](#bookmark=id.b260nup1t21v),** seeing more marketing info & not seeing (because it was below the fold on the bottom right) the next button to use to sign up
    * Suggestion:  Given that some of the following "sticky spots" are about _not having clear expectations of the signup process_, replace the reiteration of marketing info on the right half of the "Getting Started" page with a summary of the signup/next steps.  
        * (Rough) Example:  "Congratulations on making the decision to [reinvent your firm's etc etc I don't write marketing text :)]!  You can try the CTMA solution free for 30 days.  Click "Sign Up" below and we'll collect your firm information (no need to provide a payment method right now) and create your account.  You'll receive an email afterward that contains your login and instructions to setup and customize CTMA for your business."
* **[After clicking "Sign Up"](#bookmark=id.na0yxzo1bbek), **I was made hesitant / confused by the word "checkout" appearing before the checkout (money-handing-over) step, and a general lack of clarity about where in the signup process I was and how much I'd be expected to pay (and when and how).
    * In addition to outlining the steps earlier in the process, (per the above bullet-point), move the word "Checkout" to the payment-confirmation step
        * The Internet standard purchasing steps, which feel comfortable and minimize confusion, are roughly these – they can be combined onto fewer pages if they're short, but each step should require a click for selection or confirmation:
            * Select products 
            * Input information (firm info in our case)
            * Input payment information
                * This step is the earliest one that should say "checkout" – "checkout" means "this button gives your money to someone"
                * It's not a bad idea to note during this part that "You'll have a chance to click once more to confirm & finalize – Amazon does this for a reason; it helps
                * Note that if we're NOT collecting payment information, we should explain why, and when we WILL collect it – otherwise it feels fishy.
                    * Not only fishy, but worrying – what if I really want to keep my service?  When can I upgrade to the real one?  What if I forget or you don't remind me in time – will I lose my data?
                * So adding language like "No payment information is required for the Free Trial!  You'll be asked for it when it's time to upgrade" is a very good idea.
            * Confirm and finalize order 
                * this should *always* be a separate button/click, and should say something final like "Place Your Order" or "Confirm Order"
                * All the order details should be visible for review here, and there should be an easy way to back up & correct things (like if I mistyped my email or name)
        * I recommend looking at Amazon, Target, or any standard purchase-things site (most of them are using a standardized backend set of tools for this, which people are therefore used to) to see these steps in action
    * **The current price** – in our case, the monthly price and the "due now" price of $0.00 – **should always be visible** during this process.  Think of purchasing something on Amazon, etc and how the Total Price is always visible in your cart, then goes up as you select shipping info, etc.  It's very comforting & important to always see visual confirmation of the exact price you're about to pay right now – my theory is that this helps counter the inherent discomfort of the invisibility of the financial transactions we do online:  You can't see the amount of money you're physically handing over, so it helps a lot to always see it on the screen.
* **[After Purchasing](#bookmark=id.a50pvve3fxqq)** is, as I understand it, an important and easy moment to build "engagement" and improve people's opinions of & involvement with their products.  (Classic "Christmas day" syndrome – you just got the thing, now you want to play with it.)  The current order system seems to prevent this a bit – I wanted to click around more, read more, learn more, but there was nothing further to do.
    * The blank "DONE" page that comes up is…not good-feeling.  Curt and offers no further info or places to go.
        * **At minimum, it should explain that you'll be receiving an email shortly** with your login.  
        * Ideally, **it should also have a "don't see your login email?  Click here" **link that tells people to check their spam, AND how – not just because not everyone knows how, but because sometimes in following those simple instructions, folks wait long enough and the email comes through; **PLUS in order to check their spam effectively, people need to know things like "The email will come from this sender** and have this subject line" – I had Lupa email me personally to tell me that; not everyone will!  (As I mention in the details below, the email subject and sender should also be much clearer; right now they *look* like spam and are not intuitive to search for.)
            * Super-ideally, it should then have a "still don't see your email?" link where they can have the email re-sent.
            * Also super-ideally, this should then have an "email not working?" link that gives them an email or some way to contact us / put in a ticket for support.  You do want this behind a few steps, of course, and ideally you'd never use it, but you don't want someone who (potentially) just gave you money to feel like there's nowhere to turn if your email doesn't work. 
    * In addition to information about the email, the "Done" page (which I'm just going to start calling the "Success" page because it should be much more cheerful than just DONE :P) should have **links to Setup, Configuration, and Firm Settings info in our Knowledgebase** / Documentation.  
        * My reasoning for that is that this is one of the most likely times for someone to read that information, and to want to read it – or at least open the tabs & remember it for later.  Plus it's comforting to know that your next steps are there waiting for you. \

* **Emails**
    * The **confirmation email** would benefit greatly from a more detailed subject-line than "New User"
        * Makes it less likely to wind up in Spam, and more easy to find if it is in Spam (I was searching for things like "CTMA account setup" which would not have found
        * The username the email comes from being a no-reply address[^1] *and* the email containing nowhere I can click if I have problems is concerning to me – what if my login / password generation process doesn't work?  What do I do then?


            * This is arguably the worst part of the process for someone to feel like they can't reach help:  They just gave you money, but they haven't seen the product yet and have no reason to trust you.  
            * I know we don't want support calls, but we do want new users to succeed in setting up their accounts, and not to get a bad feeling at this point.  We should make sure they have all the info possible to make this process work, and that they know they have some way to get help (even if it's putting in a ticket that we can't answer immediately) if it fails.
    * I was surprised to not get an email within ~24h with **initial information** about how to get started, stuff to read, settings I should configure, etc.  
        * I then assumed I'd be given this "Startup information" when I first logged into the system, but I wasn't – I just went straight to the call center.  
        * Now, I personally will always skip the "tutorials" and just dive straight into poking at things – but most people aren't like that, lol.  And even I feel a lot better knowing that the How-To information is there if I need it.
        * Either an immediately-after-login-creation email, or an easy-to-dismiss pop-up window on first login, should point the user to whatever how-to / documentation / knowledgebase information we have to offer.  **For many people, the next step after buying something is reading the manual, **and even for those who don't read it, it's really comforting to find it in the box!
    * Another email I was expecting sometime in the first 2-3 days (it's the end of Day 3 of my trial now) was a "Welcome to your Free Trial!  Here's what to expect"-type message describing what was expected of me in the trial – Since the website didn't say this, I've been waiting to be notified that I'll be given a survey at the end, that there'll be more emails asking for my opinion, etc.  Feels a little weird to not know what the "trial" consists of or to have been formally welcomed to it.
        * I'm not, as a user, upset by this; however it does make me wonder what I should do next, and how I should communicate about things I have questions about during my trial period.


# ~More details~

(The below is less edited than the above summary; sorry if it rambles.  If any of it doesn't make sense, I'm here for questions.)


# Registration

_Note:  I registered using [philosophyisadangerousjob@gmail.com](mailto:philosophyisadangerousjob@gmail.com), an email address I'm pretty sure I haven't used to test the system before, to avoid possible weirdness from prior attempts._


## Get Started / Signup page

The **sign-up ("get started") page**, while beautiful, contains too much repetition of sales information on the right / signup side, losing focus on the necessary components.  I clicked away from this page and back at first, because it wasn't immediately obvious I was in the right place.



* The left half is clear and looks great
* The right half has **too long a header**, drowning out the phrase "TRY FOR 30 DAYS", which is the important info (also, it wouldn't hurt to specify that we mean "TRY FREE FOR 30 DAYS"; people love free trials and it isn't clear this is one)
* The right half has **too much sales info, repeated from the front page**
    * we could link back to the front page if we think folks need to ponder more; in fact, the footer already does this, but isn't currently visible because there's too much info under "Need an account?" 
    * On some browsers this is pushing the "SIGN UP" button below the fold.  Here's a screenshot from my browser (I didn't adjust this; it's how it displayed the first time) showing loss of the SIGN UP button:



<p id="gdcalert1" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image1.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert2">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image1.png "image_tooltip")




* …People should not need to scroll to see the "SIGN UP" button.


## Sign-up Page:



<p id="gdcalert2" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image2.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert3">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image2.png "image_tooltip")


A few things give me hesitation about this part:

MAJOR POINT:



* **The term "checkout" is an online ordering standard and is reserved for the final step**, where you confirm and finalize/pay for your order.  It is expected to come after one selects the product (plan), selects all details & options, and provides all necessary contact or shipping information, payment information, etc.
    * So the page that comes up when you select "Proceed to checkout" is not the Checkout page; and the button saying you're going to "Proceed to Checkout" is going to naturally make people concerned – you've skipped several steps
* **The button that says "Proceed to Checkout" should say "Enter Order Details" or similar.   \
 \
**

    MINOR POINTS:

* A new page might be better than a pop-up for the "order details" part.  A pop-up feels like the final step in ordering; it is where you "confirm" your purchase choices, and we're not to that point yet.  I'd rather see a page first that lets me select my options, before a pop-up that mentions "Checkout" and lists a price.
    * Changing this so it doesn't mention "checkout" yet may be enough
    * The price is the first thing I see, and the fact that this is a trial is just a note at the bottom.  The large price and lack of a total price for checkout of $0.00 makes it seem like I'm going to pay right now.
    * It's confusing that this is the first mention of Plans, and there's no link to further information about plans, or other options
* I think "Your Order" is the wrong terminology for this.  Better would be a page where you **specify "Order Details" **– letting people know they aren't done yet.  This could then be followed by a pop-up style page like this one showing the final selections and letting folks confirm the results.
* There would also be room on the Order Details page to offer additional information such as:
    * **"More plans coming soon" **→ So that selecting the only option, the Basic Plan, doesn't feel strange.  It is important that people select their plan, even if there's only one option; I like that this is here, but I would suggest adding a radio button – even if it's not possible to move the selection somewhere else
    * **A "Total price" at the bottom, showing that you're paying $0.00 right now – **This should always be visible.  Many online services use "Amount Due Now" and "Amount Due beginning [Date]" for this, and I find that clear.
    * A "Monthly price" showing the monthly total and the first day it will be charged
        * This will be different depending on how many seats I've selected, right?  I missed where I could see information about the Basic Plan's terms 
        * The date that my 30-day trial ends should be specified on the Checkout page or where the payment information is input; it doesn't feel good to have this be vague


## Order Completion



* The button should not say "Subscribe".  It should say "Complete my order" or similar –  This step should be a confirmation of things that have already been said before, not a new-sounding step.
    * The Price, on this (and even better, also previous) pages should specify that this is a monthly subscription.
* I was confused by the system not collecting my billing information at all – Is this step intentionally missing?  Typically, payment information is collected for free services that expire in 30 days – the fact that it wasn't is sort of nice, but it also made me concerned that my service will be canceled after the 30 days and I won't get a chance to renew it.  If we're not going to collect billing information now, we should specify when we will (i.e. "You'll be asked for your billing information 1 week before your Free Trial expires, or you can log in to add your billing info anytime").
* The post-order dialog that came up didn't make me feel confident that my order had succeeded, and it didn't tell me what to expect or do next.  This is what I saw: \
 \


<p id="gdcalert3" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image3.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert4">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image3.png "image_tooltip")
 \
 \
I would suggest adding:
    * Something confirmational:  "Success!  Your order was successful"
    * What to expect for follow-up:  "Check your email for your login details."  (Also, what do I do if I don't get an email?  I feel nervous now; I gave you my info; what if I need help?)
    * Instructions for how to do learn more about my new product now:  i.e., "Click here to read about setting up & using your new service" – I just bought the shiny new thing for my office!  I want to see more about how to set it up & get started!  
        * (Or alternately, "Login to see Tutorials and Getting Started info" – it's fine if I need to log in to see this, just let me know that's where it is.)
* **After sign up, I didn't receive an email confirmation**
    * I also didn't receive a "forgot your password" email when I tried that
    * I tried to sign up with a second email address and did not receive any emails for that either
    * Jon Lupa helpfully responded that I should search in Spam for a "bare" email that looks like this: \


<p id="gdcalert4" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image4.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert5">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image4.png "image_tooltip")

    *  …It's worth noting that I might have missed that email if it was there; **it should be updated to include more details so that people can recognize the email, **even though this wasn't the issue in my case (I still did not find the email in my spam)
    * Frank helpfully responded that the system may have not been sending an email because I didn't provide a first and last name (these are not required, so I left them blank, precisely to be this kind of pain in the butt ;)).  
        * I added a First & Last name and a Firm Name and the email came through!  
        * Using the email to generate a password went smoothly, no issues.


### Terms of Service

TBD


### Privacy Policy

TBD


# General Website Notes



1. **Image Alt Text & Hover Text** should be specified and correct (short descriptions of the content), both for accessibility reasons and because in slower browsers / if the page loads slowly, the image may not load (first) and people will see the alt text, or if not specified, the image title, instead.  The Hover text (which is sometimes the alt text, or defined separately – I didn't dive into the code to see which is being used on CTMAttorney.com) is also visible when you hover the mouse over the image, so it should be clear & not confusing.  
    1. In particular, the **main image on the front page** has alt text of "CTMA_HOME_HERO".  This is what shows up when you're hovering your mouse over the image – and that's a common place to have your mouse when the page is loading, so, for example, when I load the homepage, I often see a hovertext saying "CTMA_HOME_HERO" before anything else / before the image load.  This doesn't look as professional as proper alt text (i.e. "Image of a judge's gavel") would.
2. I, like most Internet users, have an expectation that the** logo in the upper-left corner** is a link that will lead me back to the CTMA home page, from everywhere.  This is a common breadcrumb / navigation tool, and the fact that it's missing in some places (such as in the Call Center / application) will likely frustrate some folks.


# Call Center / Application


## Firm Set-up 


## Settings & Options


## Using the software


<!-- Footnotes themselves at the bottom. -->
## Notes

[^1]:

     I noticed that the actual email address this comes from is info@connecttma, so I hit "reply" on it anyway, which some other folks will definitely do.  Ideally, if I do that, it should send me an email back saying my email was not delivered *and* telling me what to do instead if I need help.
