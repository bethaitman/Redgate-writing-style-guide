#The Redgate style guide

This guide contains advice about how to write and format anything read by people outside the company, including documentation, marketing copy, surveys, emails, and error messages.

Note that this style guide contradicts lots of our existing writing, because things have changed since then, or because there was no fixed style at the time, or someone was drunk.

##The short version

* Use plain English.

* Delete every word you don't need.

* Use American English, unless you're writing for the British market.

* Use capital letters cautiously; You Don't Need To Capitalize Everything Like This. The same applies for buttons, headings, menus, email topics, and job titles.

* Use contractions (eg it's, isn't, hasn't etc).

* Spell internet with a small i.

##Tone

The [gov.uk style guide](https://www.gov.uk/guidance/content-design/writing-for-gov-uk) says: "Write conversationally – picture your audience and write as if you were talking to them one-to-one but with the authority of someone who can actively help."

Gov.uk aims its content to be:

* informative

* clear and concise

* brisk but not terse

* incisive (friendliness can lead to a lack of precision and unnecessary words) – but human (not a faceless machine)

* serious but not pompous

We should aim for the same.

##Useful reference material

This guide is far from comprehensive. Where something isn't covered here, see also:

* the [Guardian style guide](http://www.theguardian.com/guardian-observer-style-guide-a) for sensible guidelines on all sorts of writing matters (but remember we use American English)
* the [gov.uk style guide](https://www.gov.uk/guidance/content-design/writing-for-gov-uk) for nice advice about writing plain English (but remember, again, that we use American English)
* the [Microsoft Manual of Style (fourth edition PDF)](https://ptgmedia.pearsoncmg.com/images/9780735648715/samplepages/9780735648715.pdf) for software-specific terminology. There are physical copies in the office if you'd like one. Be aware some of it's out of date, particularly when it comes to capitalization
* [Merriam Webster](http://www.merriam-webster.com) for spellings and definitions

##Alphabetical list of entries

###14-day, 28-day; 32-bit, 64-bit, etc
Adjectives (eg "try the 14-day trial").

###abbreviations and acronyms

Don't use full stops in abbreviations; eg write TFS, not T.F.S.

The first time you use an abbreviation or acronym in a page, explain it in full, and then refer to it by its initials; for example, "Team Foundation Server (TFS)". Use the abbreviation afterwards. Don't use an acronym if you're not going to use it again later in the page.

If the acronym is better understood than its expansion, don't bother spelling it out; for example, write DNS, not domain name system.

###active vs passive voice
Active voice: SQL Source Control polls the database.

Passive voice: the database is polled by SQL Source Control.

Try to use the active voice when it fits. It's usually easier to read.

###add-in
The SSMS term for plug-in. Note hyphen.

Note that Visual Studio plug-ins are called extensions.

###ampersands (&)
Don't use them. Write "and" instead.

###audience
Avoid; it's only appropriate for the entertainment business, which, glamorous as databases are, ain't our business. Say users instead.

###Amazon Web Services
The name of a product, so uppercase.

###American English
Use it. This is the English most of our users use. The exception is for job advertisements and advertising material aimed at the UK market (eg flyers at UK events, job adverts).

####words ending with -ise
Use ize instead, as with:

* synchronize
* customize
* organize

####call vs name
When talking about giving things names, such as files, use the verb name, not call. For example, "Name the column Customer."

####singular collective nouns
In American English, Redgate is a singular entity, not a collective. For example, write "Redgate is", not "Redgate are". The same goes for "Microsoft is..." and all other organizations.

###application
When talking generically about software, use application instead of program, tool, etc (eg "Close the application").

###backlog
One word.

###back up
Verb (eg "back up your database").

###backup
Noun (eg "restore a database backup").

###Beer Friday
Title case, no hyphen. (Added by request.)

###big data
Lowercase.

###bold
Since bold typefaces draw the eye, they can be used to reinforce task structure. In documentation, bold the names of things users will interact with or look for – important, active stuff, such as:

* buttons
* dialog boxes
* tabs
* panes
* text boxes
* menus
* checkboxes
For example: "To compress the backup, select the Compress backup checkbox."

###browser-based
With hyphen.

###bug-tracking system
With hyphen.

###button labels
Only capitalize the first word (eg "Link to source control").
For advice about when to use dots at the end of button names, see ellipsis.

###C#
Not c#, C Sharp, etc.

###capitals
From the Guardian: "Times have changed since the days of medieval manuscripts with elaborate hand-illuminated capital letters, or Victorian documents in which not just proper names, but virtually all nouns, were given initial caps (a Tradition valiantly maintained to this day by Estate Agents). The tendency towards lowercase, which in part reflects a less formal, less deferential society, has been accelerated by the explosion of the internet: some web companies, and many email users, have dispensed with capitals altogether."

We haven't gone as far as dispensing with capitals altogether, but we do minimize their use. Uppercase sentences used to appear in software all over the place, but it's going out of style. It looks stuffy and self-important, and is now used only by BuzzFeed headline writers. Keen to disassociate ourselves from such bottom-feeders, we only use uppercase for proper names (eg Redgate, SQL Compare, Visual Studio, Richard Mitchell). Use lowercase for most things, including:

* sentences following colons or semicolons
* headings
* button labels
* menu options
* job titles (eg software engineer, product manager)
* bullet points when the point leads from a sentence you've already started (like this one)

###canceled, canceling, canceled
One L (American English).

###caveats
Gov.uk: "Don't let caveats dictate unwieldy grammar – eg write 'You can' rather than 'You may be able to'."

###check in
Verb (eg "check in your changes").

This is the term used in Source Control for Oracle for adding changes to source control, because "commit" has another meaning  in the world of Oracle database development. SQL Source Control uses the more vanilla "commit" instead.

###check-in
Noun (eg "see your last check-in").

###checkbox
One word, no hyphen.

Despite their name, checkboxes are selected, not checked (eg "make sure all the object types are selected"), and cleared, not unchecked or deselected.

###check out
Verb (eg "Check out your order").

###checkout
Noun (eg "Go to Checkout").

###client-side
Adjective (eg "client-side server").

###clobbering
Jargon term for accidentally overwriting someone else's databases changes. It's not used everywhere, so call it "accidentally overwriting someone else's database changes" instead.

###cloud
Lowercase, because it's not a proper noun or product that belongs to someone.

###colons
Use to introduce an image or example. 

In a sentence, don't capitalize after a colon: write it in lowercase, like this.

###colors
In marketing materials, we only use the colors red, black, and white.

Redgate red is #CC0000 (hex) or R:204 G:0 B:0 (RGB). It's not the standard red that appears in Microsoft Office.

Also, note that we spell color with no u. It's the American way!

###codebase
One word.

###Oxford commas (ie a comma before the final "and" in lists)
From the Guardian: "Straightforward lists (he ate ham, eggs and chips) don't need one, but sometimes it can help the reader (he ate cereal, kippers, bacon, eggs, toast and marmalade, and tea), and sometimes it's essential: compare 'I dedicate this book to my parents, Martin Amis, and JK Rowling' with 'I dedicate this book to my parents, Martin Amis and JK Rowling'."

###columnstore index
As ugly as it looks, that's how Microsoft does it.

###command line
Two words, no hyphen.

###continuous integration
Lowercase.

###contractions (it's, can't, don't, haven't etc)
Use them. Contractions simplify and relax prose without seeming sloppy or lazy. 

Make sure you're consistent; don't write "do not" in one place and "isn't" in another.

###copyright
Stating copyright is, in the words of our own Colin Oakman, "fairly pointless". 

If you must include it somewhere, perhaps compelled at gunpoint, just write: © Redgate Software Ltd

###copyright and trademark symbols (© ® TM )
Delete them (unless you're determined to write a copyright notice, as above).

###crowdsource, crowdsourcing
One word.

###customer
Avoid, unless you're writing specifically in a sales context. 
For a generic word for users of our products, write user instead. For example: "We understand that installing updates frequently is impractical for some users."

###data
Singular; write "data is lost", not "data are lost". No one ever uses "datum".

###dates
Use this format: April 11th, 2013.

Don't use the short form (eg 11/4/1995), as the format changes depending on country.

###dependencies
When writing about databases dependencies, don't use words like dependent and depending; they look too similar and it's easy to confuse yourself (and the reader). 
Instead, use the verb "to reference", eg "object A references object B" or "object F is referenced by object G". The same goes for multiple objects: object Q references objects R and S, and is referenced by objects T, U and V.

Sometimes this makes sentences slightly awkward, but it's better to be slightly awkward and clear than succinct and incomprehensible.

###dialog box
Not dialog, or dialogue.

###dialog box titles
Use sentence case.

If the tool is a plug-in (eg SQL Source Control or SQL Prompt) and the dialog box opens in a host application, include the name of the tool in the title with an endash. For example: "SQL Source Control – History"

###disabled
Avoid; write "unavailable" instead. 

If a control is unavailable, it's often helpful to explain why.

###do, follow
Not perform or execute (unless you're talking about executing code). For example: "Follow the instructions on the Setup page."

###documentation
Not help, support, support center, etc. 

It's fine to have a Help menu in the tools, but when you link to documentation from there, write "Documentation", not "Help contents", etc.

###double-click
With hyphen.

###downloadable
Adjective. 

Use to distinguish applications that are downloaded and installed on your computer, rather than run in a browser online (ie as a service). Don't use "on-premises".

###drop-down menu
With hyphen.

###earlier (version numbers)
eg "SQL Source Control 3.2 or earlier", not older.

###early access prototype (EAP), early access release, etc
Don't use these terms; write beta instead.

###ebook
No caps or hyphen.

###eg, etc, ie
Gov.uk: "Don't use full stops after or between these notations. This was once necessary when print setting but is now cumbersome to read with modern documents and digital screens." Guardian style backs this up. We know it looks a bit like "egg", but we don't mind.

Don't put a comma after eg or ie (eg write it like this).

For reference, eg means "for example", and "ie" means "that is" (giving more information).

In most cases, writing "for example" in full is better than writing eg, but the abbreviations are appropriate in parentheses or where space is limited, like tooltips and embedded help.

###ellipsis (…)
In products (but not websites), use ellipsis - aka dot dot dot… - for button labels and menu choices where the action needs further action from the user.

A button labeled Deploy indicates the deployment will happen immediately after you click it. If you need to emphasise this, consider labeling it Deploy now.

A button labeled Deploy... indicates that the button might, for example, start a wizard, open a dialog box, or ask what you want to deploy.

On this basis, Send feedback needs ellipsis, because it requires further input from the user, but Documentation and Check for updates don't, because they do exactly what they say on the tin.

The exception: don't use ellipses for actions that produce warnings or confirmations. For example, a button labeled Delete that produces a warning dialog box asking "Are you sure you want to delete this file?" should be written without an ellipsis. This action would happen immediately - the application already has all the information it needs to do the job - but we're making extra-sure it's what the user wanted to do first.

Basically, the purpose of ellipsis is to reassure users that nothing scary will happen when they click. If something a bit scary does happen, even when buffered with a warning or confirmation, ellipsis shouldn't be used.

In documentation, when referring to a control with ellipsis in the label, don't include the ellipsis in the text. For example, write "Select the objects and click Deploy", not "Select the objects and click Deploy...".

###encountering, experiencing
In the world of software, these are euphemisms for "having", and so it's usually simpler to write "have" instead. For example: "If you still have problems, contact Redgate support."

###enter
Use for fields you type stuff into. For example: "Enter the database name."

###email
No hyphen, no capital.

###email address
Unless you need to avoid ambiguity, just write email.

###error messages
Error messages are important. They're an integral part of the user experience, and users are far more annoyed by bad error messages than they are delighted by a cool UI.

* Explain, in the following order: what went wrong, why, and (if possible) how to fix it.

* Be precise. If the cause is unknown, say so.

* Be succinct. Users don't want to read an essay. They may search Google or our documentation for the error text, or quote it to the support team, so make sure it's as concise and readable as possible.

* Link to any relevant documentation. If you're not sure if there's a page describing the problem, ask a technical writer. If there isn't one and you think there should be, shout at a technical writer.

* Provide a Close button rather than OK. Having to click "OK" when an application fails makes the user feel like they're being held hostage and forced to agree to bad things.

* Don't try to be apologetic ("Sorry, your data couldn't be recovered") or funny ("Yikes! Where'd your data go?"). Keep the tone neutral and stick to the facts.

* Is the message a warning (ie something bad might happen if you continue)? Use a yellow triangle. Is it an error (ie something bad already happened)? Use a red stop icon.

* Typos add insult to injury and give a poor impression of the quality of our tools. Read the message out loud to find mistakes, and get someone else to review it.

* Where is the error message displayed? Is it a separate dialog box or in a GUI? If it's a separate dialog box, its title should typically contain the name of the application.

* Would someone who isn't a developer for this application understand the problem described?

###extension
Not file extension or file name extension.

Don't capitalize extensions followed by a full stop; for example, write .csv, .html, .sql, etc. If you use an extension as the last word in a sentence, don't follow it with a full stop; eg write "Download as a .chm".

Capitalize file types when you're not writing them as extensions; for example, HTML file, SQL file, etc.
The exception is PDF, which has become its own word (eg "available as a PDF"). For this reason, it's fine to write PDFs plural, rather than PDF files.

###file path
Two words, no hyphen.

###file name
Two words, no hyphen.

###fill out (for surveys)
Not fill in. (American English.)

###first-time
Hyphenate only when used as adjective; eg first-time user, first-time comparison, etc.

###fix
Not rectify, repair, correct, resolve, or solve. 

Use to describe something that actually fixes the problem rather than works around it (see workaround).

###flyer
Many US style guides recommend flier, but flyer is the more common US spelling.

###focused, focusing
One s: not focussed or focussing.

###free
Not for free; eg "SQL Search is available free".

###MB, GB, Mb, Gb
MB, GB: for hard disks, memory and file sizes. (An uppercase B indicates bytes.)

Mb, Gb: for network connections. (A lowercase b indicates bits, not bytes.)

Write both without a space after the number, eg 100MB.

###gender
Our software is used by men and women, and our writing should reflect that.

Never say "his" to refer to a user generically. It's fine to use they/them/their (eg "The user can link their database to source control").

To counter the predominantly male language of software and database development, it's nice to include female names in screenshots, worked examples and so on (eg "Amanda creates a table in her database and goes to the Commit changes tab").

###Git
Uppercase G.

###GitHub
No hyphen.

###host name
two words.

###hover over
Avoid. Write "move the mouse over" instead.

###icons
Sometimes it's more helpful to include an image of a UI element rather than describe it.

If the icon comes at the end of the sentence, don't follow it with a full stop.

###information about
Not information on.

###internet
With a small i, no matter what the Microsoft style guide or the surly developer on your team thinks. There's no sensible rationale for capitalizing it as a proper noun, and it's old-fashioned.

###the internet of things
Lowercase.

###into/in to
In the words of the Guardian style guide: "One word if you go into a room or look into something, but two words in such sentences as I called in to complain, I listened in to their conversation and I went in to see my friend."

For us, this means one word in sentences such as "Log into your Redgate ID" and "Check changes into source control".

###impact
A noun, not a verb. Things have an impact; they don't impact things. (The verb you're looking for is "affect").

###italics
Italicize:

* things a user can type or specify (eg "Type or select *WidgetStaging*")

* file names (eg "Open *SQLScript.sql* in your SQL editor")

* file paths (eg "Go to *C:\Program files\Red Gate\SQL Compare 7*")

* new terms to distinguish them from the rest of the sentence, because it'll look weird if you don't (eg "*Whenever you compare databases, you set up a project*")

###jargon
"The practice of never calling a spade a spade when you might instead call it a manual earth-restructuring implement." - Bill Bryson

Like all offices, Redgate has a high volume of jargon, including old favorites such as:

* going forward

* at this moment in time

* end of life (as a verb)

* sunset (as a verb)

* impact (as a verb)

* drill down

* starting every possible sentence with the word "so"

Using language like this to communicate internally is one thing. But please don't use it in something a user will read.

The world of database and software development has its own jargon, of course, and this should be avoided too. For example, accidentally overwriting someone's database change is known colloquially as "clobbering", but "accidentally overwriting changes" is clear and neutral to everyone who reads it.

###JavaScript
Uppercase S.

###job titles
Lowercase. For example, James Duffy is a technical writer, not a Technical Writer.

###later (version numbers)
eg "SQL Source Control 3.2 or later", not higher.

###left-hand, right-hand
Adjectives.

###lets you, enables you, allows you (eg "SQL Source Control enables you to source-control your databases")
Avoid. "Enables" is wordy marketing speak, and "lets" and "allows" sound like SQL Source Control is giving you permission to do something.

Instead, write "With SQL Source Control, you can source-control your databases". Better yet, find a way to write it as a straightforward active sentence, describing what the tool itself does: "SQL Source Control links your database to your source control system."

###license
Not licence. This goes for both nouns and verbs. (American English.)

###links
Don't use anything like "click here" for a link; there's always a better way of doing it.

Ideally, the title of the page you're linking will be self-explanatory. In these happy cases, write "[see Deploying data sources](http://documentation.red-gate.com/display/SC10/Deploying+data+sources)", not  "read about Deploying data sources [here](http://documentation.red-gate.com/display/SC10/Deploying+data+sources)".

If the information you're talking about isn't obvious from the page title, explain what information it contains before you link: "For more information about the working base, see the [architectural overview](http://documentation.red-gate.com/display/SOC3/Technical+overview)." Use "the" before the link if it makes sense, as in this example, but don't make it part of the link, and don't capitalize afterwards.

If you're short of space in a UI, it's OK to just write "[Learn more](http://documentation.red-gate.com/display/SC10/Setting+project+options)" (without a full stop). For example: "You can change the SQL Compare behavior by editing the comparison options. Learn more". It's tempting to make part of the text into a link (eg "[You can change the SQL Compare engine behavior by editing the comparison options](http://documentation.red-gate.com/display/SC10/Setting+project+options)"), but in the context of a product rather than a website, this might be mistaken as performing an action rather than opening documentation.

Punctuation (eg full stops and commas) following the link should never be part of the link text.

###lists
Lists make things easy to read. Use them!

If each item in the list is a sentence, use sentence case: capitalize the first word and end with a full stop.

* This is a sentence, for example.

* This is also a sentence.

* This is a sentence too.

If the items are fragments, or follow an introduction marked with a colon, use lowercase with no full stop. For example, these:

* are fragments
* that continue from the introductory "these:" sentence
* so don't take sentence case

Don't use "and" before the last item.

Don't mix styles in the same list.

###log in, log out
Verbs (eg "Log into your Redgate ID").

Avoid other forms such as log on/off, sign in/out, sign off.

###login
Noun (eg "I've forgotten my login details").

###logos
Make sure you use the right Redgate logo.

The Redgate logo uses the curvature font. This font shouldn't be used elsewhere under any circumstances.

The black logo should only be used on a white or red background. The white logo should only be used on a black background.

You can get logos from W:\Public Design Work\LOGOS_x\LOGOS

###make sure
Not ensure, which sounds pompous.

###metadata
One word.

###might
Not may.

###migration script
Not migrations script. No caps.

###monospace
Use monospace when you want to embed a bit of code or script in normal text, or when you're quoting from text in an XML or SQL file, or a command line, or other techy text thing. 

For example: "You can change the value in the <QueryTimeInMillis> tags to the interval you want."

###mouse and key actions
Capitalize as most keyboards do, like this:

* click
* right-click
* double-click
* Ctrl
* Alt
* Shift
* Enter
* Backspace
* Space (not the space bar)
* Tab
* Caps Lock
* A, B, C etc (for letter keys)
* F1, F2 etc

Use "+" for simultaneous actions. For example: "Highlight the objects with Shift + click or Ctrl + click."

###mouse wheel
Not scroll wheel or wheel button.

Not to be used as a verb object; write "scroll using the mouse wheel", not "scroll the mouse wheel".

###n/a
Lowercase.

###numbers
Spell as words from one to nine. After that, use digits: 10, 11, 12...

If you have both in the same sentence, only use digits.

###no one
No hyphen.

###Object Explorer
Uppercase, because Microsoft named it, not us.

###OK
Write this as an abbreviation instead of "okay", without full stops. This applies to UI (eg OK buttons) and everything else.

###online
No hyphen.

###open source
As a noun, no hyphen: eg "our development model is open source".
As an adjective, hyphenate: eg "this is open-source software".

###Oracle product names
We're legally unable to put Oracle at the start of our names for Oracle database products, since it sounds like they're made by Oracle the company. So:

* Data Compare for Oracle
* Schema Compare for Oracle
* Schema Doc for Oracle
* Source Control for Oracle

###overly
You wouldn't write "underly", so don't write "overly".

Write "overcomplex", "overqualified", etc. If you're unconvinced, use "too" instead.

###page
When referring to content on documentation.red-gate.com, use "page" instead of "topic" or "article".
page titles, headings, email subjects etc

Use sentence case. This means you capitalize only the first word of the heading; subsequent words are all lowercase (except for proper nouns, acronyms, etc).

On documentation page titles, don't specify the product name prior to the title (eg "SQL Source Control: Setting up"). It's unnecessary, because that page is already in the SQL Source Control space.

For "how to" pages, use gerunds (eg "Creating backups"). Don't use questions (eg "How do I create a backup?").

For troubleshooting pages about error messages, use the error message (truncated if very long) for the title. Otherwise, state the problem in the present tense in the terms users are most likely to google (eg "Can't run two database backups at the same time").

###photography
Stock photography is banned on account of being boring. 

Photographs of real people and situations are OK.

###please
Be careful. "Please" can make writing feel cold and teacherly. For example, "To view source control history, go to the History tab" sounds more helpful and neutral than "To view source control history, please go to the History tab".

The exception is if we're asking users to do something that principally benefits Redgate and not them. For example:

"Although we test updates thoroughly before releasing them, some of the updates on the frequent release channel might not work with your environment. If that happens, please contact Redgate support so we can fix it."

Though it does benefit the user to get their bugs fixed, this example is more about asking users to report bugs so we can do our job better. We're basically asking a favour of them, so "please" is appropriate.

###plug-in
With hyphen; but note that SSMS plug-ins are called add-ins and Visual Studio plug-ins are called extensions.

###prerequisite
Avoid. Use "requirement" instead.

###program
Never programme, which is British. (But remember, as a noun, we generally prefer application anyway.)

###PS
No full stops (in this or any other acronym).

###quotation marks
Use double quotation marks ("). Use single quotation marks (') for quotations within quotations.

###re/re-
Use re- (with hyphen) when followed by the vowels e or u (not pronounced as "yu"): eg re-entry, re-examine.

Use re (no hyphen) when followed by the vowels a, i, o or u (pronounced as "yu"), or any consonant: eg reinstall, reassemble, reorder, reread, reuse, rebuild, retry.

Exceptions where confusion with another word would arise: re-cover/recover, re-creation/recreation, re-form/reform, re-sent/resent, re-run/rerun.

###Redgate
As of January 2015, Redgate is spelled as one word. As Simon G sez:

"About 80% of the time when I tell people our company name and they've never seen it written down, they assume it's Redgate. For fifteen years now, we've been correcting them, but recently we've come around to the idea that maybe we should be correcting ourselves. If our logo, our URL and our company name were all Redgate, wouldn't that be simpler for people to understand and remember?

Our answer has always been that it's more correct and grammatical to spell it Red Gate, and Neil much preferred it to be spelt that way – no doubt some grammar gods will be upset by this decision. But ingenious simplicity is a higher calling than being right for the sake of being right whilst being wrong for our customers.

From now on, we're spelling the company name Redgate. The main reason behind this decision is that we've been confusing our customers (and ourselves) for too long by spelling the company name half a dozen different ways. Of all the spelling options, Redgate is the simplest, and thus the easiest to remember and to find."

Likewise, it's Redgate, not Redgate Software. 

When you're writing the company name in a legal capacity, such as in the footer of websites, write Redgate Software Ltd.

Don't include Redgate in product names (eg write SQL Compare, not Redgate SQL Compare).

Remember: in American English, Redgate is a singular entity (eg "Redgate is a company", "Redgate issues software updates").

###right-click
Verb (eg "Right-click the file").

This doesn't need "on" after it; for example, write "right-click the object", not "right-click on the object".

###Save as...
Not Save file as, Save project as, etc. The exception is to use "Save project as…" where it disambiguates from an existing "Save as…" option.

Note ellipsis, because it requires further input from the user (see ellipsis).

###schema, schemas
Not schemata. (Yes, people have used this.)

###screen

Not to be used to describe any bit of a UI. Be specific: is it a dialog box, tab, pane, or page?

###screenshot
Not screen or screengrab. 

###scrollbar
One word, no hyphen.

###see
Not refer to.

###semicolons
OK in some situations, but always consider using a full stop instead. In technical writing, semicolons can be frilly and ambiguous.

A rule of thumb: unless you're writing a list, if you can't replace your semicolon with a full stop and still have the sentence make sense, you've probably gone wrong.

If you're not confident with semicolons, don't use them. Leave them to the mad poets and dreamers. (But if you're curious, there's a [good guide to semicolons on WikiHow](http://www.wikihow.com/Use-a-Semicolon).)

###server
Lowercase. Unless you're talking about the Microsoft product SQL Server, which is uppercase. eg "The server that SQL Server is installed on"

###server-side
Adjective.

###set up
Verb (eg "Set up the database comparison")

###setup
Noun (eg "Follow the setup instructions").

###shown, opens
Not displayed (nasty passive voice) or appears (sounds like a magic trick).

Remember to use the active voice where you can: eg "The History dialog box opens" is better than "The is History dialog is shown".

###Simple Talk
Uppercase, no hyphen, with space.

###slashes
Use for combinations (eg client/server), not as a substitute for "or". 

Only use spaces when there are multiple words on at least one side of the slash (eg "database administrator / database developer").

###source control
Not version control or revision control. 

Version control is the more widely used term, but our source control products are named SQL Source Control and Source Control for Oracle, so we should err on the side of consistency... for now.

As a noun: source control (eg "Link your database to source control").

As a verb: source-control (eg "You can source-control your database").

As an adjective: source-controlled (eg "Your database is source-controlled").

Never refer to SQL Source Control without "SQL" as "Source Control", as it looks like you're talking about source control the concept, rather than SQL Source Control the application.

###spacing after a full stop
Use a single space, not double. (The oft-supplied historical explanation for this [may be apocryphal](http://www.heracliteanriver.com/?p=324), but who cares? Single spaces look better.)

###specify
Generic verb for providing information about something. Use this for forms with multiple controls (eg a combination of radio buttons and text fields). For example: 
"Specify connection details."

If you're only talking about text fields you type into, use "enter".

###spelled vs spelt

"Spelled" is the more common American spelling. As our own Michael Upton points out, spelt is more familiar to Americans as "dinkel wheat, or hulled wheat … an ancient species of wheat from the fifth millennium BC".

###SQL Comparison SDK
The name of a product, so use uppercase. 

Write "the" before it in sentences, or it looks weird. For example: "With the SQL Comparison SDK, you can use the functionality of SQL Compare, SQL Data Compare, and SQL Packager in your own applications."

###SQL Server
Uppercase, eg "The base monitor is a Windows service that monitors your SQL Servers". "SQL Servers" means "instances of SQL Server".

The computer that SQL Server is installed on is just a "server". 

###SQL Server Database Project
Uppercase.

###SQL Server Management Studio
It's fine simply to write "Management Studio". (Microsoft does.)

###start up
Verb (eg to start up a computer).

###startup
Noun; the event of starting up (eg check for updates on startup).

###sub-
Don't hyphenate words that begin with sub. Instead, write subfolder, subheading, subsection, subdomain, etc.

###support
No caps, even when referring to Redgate support (eg "contact Redgate support").

###sync
Not synch. (But remember: our comparison tools don't synchronize or sync database changes, they deploy them.)

###SQL tools
Not a product name, so tool is lowercase.

###table-valued function
With hyphen.

###taskbar
One word, lowercase.

###technical writer, technical communications, tech comms
Lowercase (as with job titles).

###time out
As a noun, with hyphen; eg "time-out".

As a verb, without hyphen; eg "the server request timed out".

###that, which, of
Can often (but not always) be removed without losing meaning or clarity; eg "choose the database that you want to source-control"; "select all of the objects".

But clarity is more important than brevity, so don't delete it if you think it's clearer.

###that or which?
"That" defines. "Which" gives extra information, often in a clause enclosed by commas or brackets.

| Sentence   | Meaning  |
| The classrooms, which were painted last summer, are bright and cheerful.  | All the classrooms were painted last summer. They're bright and cheerful. | 
| The classrooms that were painted last summer are bright and cheerful. | Only some of the classrooms were painted last summer. Unlike the unpainted ones, the painted classrooms are bright and cheerful. | 

###third party
Noun.

###third-party
Adjective (eg a third-party company).

###tooltip
One word, lowercase.

###tooling
The word normal humans use is "tools".

###update vs upgrade
Updates are minor releases - eg SQL Monitor 3.1 to 3.2.

Upgrades are major releases - eg SQL Monitor 3 to 4.

###UK-based
With hyphen.

###uninstall
One word, contrary to some of our engine tests' haughty demands.

###up to date
But up-to-date drivers (as an adjective). For example: "The drivers are up to date", but "Download up-to-date drivers".

###user
The best generic term for a user of our products (as opposed to, for example, customer).

###user base
Two words, no hyphen.

###user-defined
Adjective, hyphen.

###username
One word when referring to the name part of a login. (Read the comments for a fascinating debate about this.)

###want
Not wish (we're not genies). For example, write: "If you want to add a new database to source control..."

###web, website, web browser, web address, web page
No capitals.

Unless you want to sound like a square from the past, don't say "the web" on its own; say "the internet" instead.

###we and us
It's OK to write "we" or "us" to mean Redgate, especially as it means we avoid the passive voice; eg write "We recommend you do X", not "You are recommended to do X".

###whilst
Avoid. Though still in common use in British English, whilst is becoming old-fashioned; in American English, it's Shakespearean. Use "while" instead.

###WinForms
Note capitals. 

An ugly name for an ugly thing.

###with
Be careful. When written to mean using, this can lead to unwanted ambiguity. For example, "select the objects with the checkboxes" could be read as "select the objects that have checkboxes" or "select the objects and the checkboxes".

###white paper
Two words.

###white space
Two words.

###workaround, work around
Noun: workaround (eg "You can use the following workaround to…"). 

Verb: "work around" (eg "work around the problem").

A workaround doesn't fix a problem. Instead, it allows the user to get on with their lives until we provide a proper fix.

###zoom in, zoom out
No hyphen.

##How to write particular things

###Release notes
Our release notes have been wildly inconsistent over the years. Here's our recommended format, with an example afterwards:

#####Features
* Exclude words like "you can..." For example, don't write: "You can now change the number of items shown in the History dialog". Instead, write: "Change the number of items shown in the History dialog".

* List new features (and enhancements, performance improvements etc) in the release as bullet points, without full stops.

* List the features approximately in order of importance. If there's one major new feature, put it before smaller ones.

* Link to relevant documentation where appropriate (eg a page describing the feature in more detail). 

* If a feature involves changes to the UI, consider including a screenshot. This is good advertising; everyone likes a new UI.

#####Fixes
* Use terms such as "now" and "no longer" to clarify that you're describing how the tool behaves in this release. Otherwise, it may sound as if you're describing the bug, not the fix. For example, don't write "Materialized views script hidden fields", as it's not clear if that's what used to happen, or what happens now. Instead, describe what the fix has changed; eg write "Materialized views no longer script hidden fields", or "Materialized views now script hidden fields", depending on what's changed.

* If the bug has a Jira reference (eg SB-5415), include it at the start of each bullet point, followed by a colon. If the same issue has multiple bug codes, include them all in the same bullet point.

* List the fixes in numerical order according to the bug code.

* If the fixes have relevant documentation, link to it.

#####Known issues
* If the release introduces new issues or bugs, list them.

* If the issues have bug numbers, list them.

* Link to any relevant resources.

#####Example release notes

######Features

* Upload backup copies to a SQL Backup Pro Hosted Storage account
* Manage offsite backups from the SQL Backup Pro Hosted Storage website
* View results of copying backups to hosted storage or a network location from the Activity History and Backup Properties

######Fixes

* SB-5415: When installing the server components with the /Log switch, account passwords are no longer recorded in plain text in the log
* SB-5446: The SQL Backup server components installer now checks that the user is a member of the SQL Server sysadmin role before attempting the installation

######Known issues

* SQL Backup Pro doesn't support installation on Windows Server 2012 with Failover Clustering. For more information, see Installing


###Usage reports
[ ] Send anonymous usage statistics and error reports to Redgate

We use these statistics to improve our tools.
