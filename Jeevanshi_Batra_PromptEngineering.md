# Prompt Engineering Portfolio

Name: Jeevanshi Batra
Date: 02 June 2026
LLM Used: ChatGPT (GPT-5.5)

## Part 1: Prompt Design & Iteration
### 1.1 Scenario A: Technical Explanation

#### Initial Prompt (V1)

```text
Explain blockchain to a 10-year-old child.
```

#### Output V1

```text
Imagine you and your friends have a notebook where you write down every time someone trades a toy.

If Rahul gives a toy car to Priya, everyone writes it in their copy of the notebook.
Once something is written, nobody can secretly erase or change it because everyone else has the same record.
New pages are added to the notebook over time, and each page is linked to the previous one, forming a chain of pages.

That's basically what a blockchain is:

Block = a page of records.
Chain = pages connected together in order.
Blockchain = a digital notebook shared by many computers.

Because lots of computers keep the same copy:
✅ It's hard to cheat.
✅ Everyone can check the records.
✅ No single person controls the notebook.

A simple example:
If you send 5 game coins to your friend, the transaction is recorded in a block. That block gets added to the chain, and everyone can see that the coins moved from you to your friend.

So, blockchain is like a shared, super-secure digital notebook that keeps track of information and is very difficult to tamper with.
```

#### Refined Prompt (V2)

```text
Explain blockchain to a 10-year-old child using simple words and a real-life example.
```

#### Output V2

```text
Imagine you and 20 kids in your class are collecting cricket cards.

One day, Rohan gives a Virat Kohli card to Ananya. To make sure nobody lies later, every child writes this trade in their own notebook:

"Rohan gave 1 Virat Kohli card to Ananya."

Now, if Rohan later says, "I never gave that card," everyone can check their notebooks and prove what really happened.

How Blockchain Works
A block is like one page of the notebook containing several records.
When a page is full, it is added to the notebook.
The next page is connected to the previous page, creating a chain of pages.
This is why it is called blockchain.
Real-Life Example

Think of a Google Doc that is shared with thousands of people.

Everyone can see the same information.
If someone tries to secretly change a record, others will notice because their copies are different.
This makes cheating very difficult.
Why People Use Blockchain

✅ To keep records safe
✅ To prevent cheating or fraud
✅ To track things like money, tickets, or ownership of items
✅ To let many people share the same trusted information

In One Sentence

Blockchain is like a giant shared notebook that many people own together, where everyone can see the records and nobody can secretly change them. 📒🔗
```


#### Final Prompt (V3)

```text
You are an expert elementary school teacher. Explain blockchain to a 10-year-old child using very simple language, a fun analogy, and a short example. Avoid technical jargon and keep the explanation under 150 words.
```

#### Final Output

```text
Imagine a magic class notebook that everyone in the class can see.

Whenever someone trades a sticker, the trade is written in the notebook. For example:

Aarav gives 1 football sticker to Maya.

Before it's added, the whole class checks that it's true. Once everyone agrees, the note is written down and cannot be erased.

Each page is connected to the page before it, like links in a chain. That's why it's called blockchain.

Fun analogy:
Think of blockchain as a shared treasure journal. Everyone has a copy, so nobody can secretly change the story or steal treasure without everyone noticing.

Short example:
If Maya gets a sticker from Aarav, the trade is recorded in the journal. Later, if someone forgets what happened, everyone can check the journal and see the same record.

Blockchain is a shared record book that helps people keep information safe and honest. 📖🔗
```

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Explain blockchain to a 10-year-old child. | N/A | N/A |
| V2 | Explain blockchain to a 10-year-old child using simple words and a real-life example. | Added simple language requirement and real-life example. | Made the explanation easier to understand and more relatable for a child. |
| V3 | You are an expert elementary school teacher. Explain blockchain to a 10-year-old child using very simple language, a fun analogy, and a short example. Avoid technical jargon and keep the explanation under 150 words. | Added role assignment, fun analogy, output length limit, and instruction to avoid technical jargon. | Produced a clearer, more engaging, and age-appropriate explanation. |


### 1.1 Scenario B: Professional Email

#### Initial Prompt (V1)

```text
Write an email declining a job offer politely.
```

#### Output V1

```text
Subject: Thank You for the Job Offer

Dear Hiring Manager,

Thank you very much for offering me the position of [Job Title] at [Company Name]. I appreciate the time and effort you and your team invested throughout the recruitment process.

After careful consideration, I have decided to decline the offer at this time, as I have chosen to pursue another opportunity that aligns more closely with my current career goals.

I am grateful for the opportunity to learn more about your organization and meet the team. I wish you and [Company Name] continued success, and I hope our paths may cross again in the future.

Thank you once again for your understanding.

Kind regards,
[Your Name]
[Phone Number]
[Email Address]
```

#### Refined Prompt (V2)

```text
Write a professional email declining a job offer politely while expressing continued interest in the company and future opportunities.
```

#### Output V2

```text
Dear Hiring Manager,

Thank you very much for offering me the position of **[Job Title]** at **[Company Name]**. I sincerely appreciate the time and effort you and the team invested throughout the interview process.

After careful consideration, I have decided to decline the offer at this time. This was not an easy decision, as I was impressed by the company's culture, values, and the opportunities for growth that your organization provides.

While I will not be joining the team at this moment, I remain very interested in **[Company Name]** and would welcome the opportunity to be considered for suitable roles in the future. I have great respect for your organization and hope our paths may cross again.

Thank you once again for your confidence in my abilities and for the positive experience throughout the recruitment process. I wish you and your team continued success.

Kind regards,

[Your Name]
[Phone Number]
[Email Address]
```

#### Final Prompt (V3)

```text
You are an experienced HR professional. Write a professional and courteous email declining a job offer because the position does not align with my current career goals. Express gratitude for the offer, maintain a positive relationship with the company, and show interest in future opportunities. Keep the tone respectful and professional.
```

#### Final Output

```text
Dear [Hiring Manager's Name],

Thank you very much for offering me the position of [Job Title] at [Company Name]. I sincerely appreciate the time, effort, and consideration extended to me throughout the recruitment process.

After careful thought, I have decided to decline the offer, as I believe the role does not align closely with my current career goals and professional aspirations. This decision was not easy, given the positive impression I have of your organization and the professionalism demonstrated by everyone I had the opportunity to meet.

I am truly grateful for the opportunity and for the confidence you have shown in my abilities. I hold [Company Name] in high regard and would welcome the possibility of exploring future opportunities that may be a better fit for my career path.

Thank you once again for your understanding. I hope to stay connected and wish you and your team continued success.

Warm regards,

[Your Name]
[Phone Number]
[Email Address]

```

### 1.1 Scenario C: Creative Content

#### Initial Prompt (V1)

```text
Create a marketing tagline for an eco-friendly water bottle brand.
```

#### Output V1

```text
Here are several tagline options for an eco-friendly water bottle brand:

Sip Sustainably. Live Responsibly.
Good for You. Better for the Planet.
Every Refill Makes a Difference.
Drink Clean. Stay Green.
Hydration with a Purpose.
Refill Today. Protect Tomorrow.
Carry Water, Not Waste.
Sustainable Sips for a Better Future.
Choose Reuse. Choose Change.
One Bottle. Endless Impact.

For a modern, memorable brand feel, "Carry Water, Not Waste." is particularly strong because it's short, clear, and directly communicates the environmental benefit.
```

#### Refined Prompt (V2)

```text
Create a catchy and memorable marketing tagline for a new eco-friendly water bottle brand targeted at environmentally conscious consumers.
```

#### Output V2

```text
Here are some catchy tagline options for an eco-friendly water bottle brand:

Refill the Bottle. Renew the Planet.
Sip Smart. Live Green.
Hydrate Naturally, Protect Globally.
Every Sip Supports the Earth.
Drink Better. Leave Less Behind.
Pure Hydration, Zero Compromise.
Carry Change in Every Bottle.
Refresh Yourself. Respect the Planet.
One Bottle, Countless Greener Choices.
Stay Hydrated. Stay Earth-Friendly.

Recommended tagline:
"Every Sip Supports the Earth."

It's simple, memorable, emotionally engaging, and directly connects the customer's daily action with a positive environmental impact.
```

#### Final Prompt (V3)

```text
You are a professional copywriter for sustainable brands. Create 10 creative, memorable, and emotionally appealing taglines for a new eco-friendly water bottle brand. The taglines should highlight sustainability, reducing plastic waste, and healthy living. Keep each tagline under 10 words.
```

#### Final Output

```text
Sip Clean. Leave Nothing Behind.
Refill Today. Protect Tomorrow.
Drink Well. Tread Lightly.
Hydration That Helps the Planet.
Less Plastic. More Life.
Carry Water, Not Waste.
Healthy You. Healthier Earth.
Every Refill Changes the Future.
Pure Water. Cleaner World.
One Bottle. Endless Positive Impact.
```

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Write an email declining a job offer politely. | N/A | N/A |
| V2 | Write a professional email declining a job offer politely while expressing continued interest in the company and future opportunities. | Added professionalism and future interest. | Made the email more courteous and relationship-focused. |
| V3 | You are an experienced HR professional. Write a professional and courteous email declining a job offer because the position does not align with my current career goals. Express gratitude for the offer, maintain a positive relationship with the company, and show interest in future opportunities. Keep the tone respectful and professional. | Added role assignment, specific reason, gratitude, and professional tone requirements. | Produced a more realistic and polished business email. |

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Create a marketing tagline for an eco-friendly water bottle brand. | N/A | N/A |
| V2 | Create a catchy and memorable marketing tagline for a new eco-friendly water bottle brand targeted at environmentally conscious consumers. | Added target audience and creativity requirements. | Generated more relevant and engaging taglines. |
| V3 | You are a professional copywriter for sustainable brands. Create 10 creative, memorable, and emotionally appealing taglines for a new eco-friendly water bottle brand. The taglines should highlight sustainability, reducing plastic waste, and healthy living. Keep each tagline under 10 words. | Added role assignment, quantity, emotional appeal, and brand focus. | Produced stronger marketing-focused taglines with clear messaging. |


### 1.3 Role and Context Analysis

Role assignment significantly improved the quality of the outputs by making the LLM respond from a specific perspective. For example, assigning the role of an elementary school teacher resulted in a more child-friendly explanation of blockchain. Similarly, using the role of an HR professional produced a more realistic and professional email. Context setting helped by clearly defining the audience, purpose, tone, and constraints of each task. Together, role and context made the outputs more accurate, relevant, and useful.
















