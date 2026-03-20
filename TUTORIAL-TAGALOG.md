# Gabay sa Paggawa ng Agent Skills (Step-by-Step Tutorial)

> Pang-beginners na gabay kung paano gumawa ng sariling Agent Skills. Walang technical jargon — puro practical lang!

---

## 📋 Table of Contents

1. [Ano nga ba ang Agent Skills?](#ano-nga-ba-ang-agent-skills)
2. [Bakit Kailangan Mo 'To?](#bakit-kailangan-mo-to)
3. [Kailangan Mong Ihanda](#kailangan-mong-ihanda)
4. [Step 1: Mag-setup ng Skills Folder](#step-1-mag-setup-ng-skills-folder)
5. [Step 2: Gumawa ng Iyong Unang Skill](#step-2-gumawa-ng-iyong-unang-skill)
6. [Step 3: I-test ang Iyong Skill](#step-3-i-test-ang-iyong-skill)
7. [Step 4: I-improve Base sa Results](#step-4-i-improve-base-sa-results)
8. [Common Problems at Solusyon](#common-problems-at-solusyon)
9. [Real-World Examples Para sa Pinoy](#real-world-examples-para-sa-pinoy)

---

## Ano nga ba ang Agent Skills?

**Simple explanation:** Agent skills ay parang **"cheat sheets" na binibigay mo sa AI assistant** para alam niya kung paano mag-handle ng specific tasks.

**Halimbawa:**
- Sa halip na paulit-ulit mong i-explain kung paano mo gusto ang email replies mo...
- Gawa ka ng "Email Reply Skill" 
- Pag may email na, automatic alam na ng AI ang tone, format, at style na gusto mo!

**Isipin mo na parang:**
- 📚 Recipe book para sa AI
- 🛠️ Toolbox na pwede niyang gamitin anytime
- 🎯 Playbook para sa paulit-ulit na tasks

---

## Bakit Kailangan Mo 'To?

### ✅ Benefits para sa Everyday Pinoys:

1. **Tipid sa Oras** - Hindi ka na mag-type ng mahabang instructions every time
2. **Consistent ang Quality** - Same quality lagi, hindi nakadepende sa mood mo
3. **Madaling I-share** - Pwede mo i-share sa team or community
4. **Scalable** - Pwede kang gumawa ng maraming skills para sa iba't ibang tasks
5. **Di mo kailangan coding skills** - Plain text lang, Taglish pa!

### 🎯 Perfect for:
- Freelancers (client management, proposals)
- Online sellers (product descriptions, customer service)
- VA's (email handling, scheduling)
- Small business owners (social media, inventory)
- Students (research summaries, study guides)

---

## Kailangan Mong Ihanda

### 1. **AI Assistant na may Skills Support**
Mga pwede mong gamitin:
- ✅ Claude (via Anthropic)
- ✅ Cursor IDE (for developers)
- ✅ Custom agents gamit ang frameworks

### 2. **Text Editor**
Kahit ano basta kaya mag-save ng `.md` files:
- VS Code (recommended, free)
- Notepad++ 
- Kahit basic Notepad okay na

### 3. **Folder kung saan mo save-an ang skills**
Example:
```
📁 MyAgentSkills/
   📄 email-reply-skill.md
   📄 social-media-post-skill.md
   📄 client-proposal-skill.md
```

---

## Step 1: Mag-setup ng Skills Folder

### 📸 Screenshot Guide:

**1.1 - Gumawa ng Folder**

```
Windows:
Right-click sa Desktop → New → Folder → Name it "MyAgentSkills"

Mac:
Control-click sa Desktop → New Folder → Name it "MyAgentSkills"
```

**1.2 - Buksan sa Text Editor**

```
Open VS Code → File → Open Folder → Select "MyAgentSkills"
```

✅ **Dapat ganito ang itsura:**
```
MyAgentSkills/
└── (empty pa)
```

---

## Step 2: Gumawa ng Iyong Unang Skill

Let's gumawa ng **"Email Reply Skill"** - perfect para sa mga nag-rerespond ng maraming emails!

### 📸 Step-by-Step:

**2.1 - Create New File**

Sa VS Code:
1. Click "New File" icon OR press `Ctrl+N` (Windows) / `Cmd+N` (Mac)
2. Save as: `email-reply-skill.md`
3. Make sure naka-save sa loob ng `MyAgentSkills` folder

---

**2.2 - Copy-Paste ang Template**

```markdown
# Email Reply Skill

## Description
Skill na tumutulong sa pag-reply ng professional emails with Filipino communication style.

## When to Use
Use this skill when:
- May customer email na kailangan sagutin
- May inquiry from potential client
- May follow-up email sa existing client
- Need ng professional pero friendly na tone

## Instructions

### Tone & Style:
- Professional pero approachable
- Use "po" and "opo" when appropriate
- Warm but respectful
- Clear and concise

### Email Structure:
1. **Greeting**
   - Use proper salutation based on time:
     - Morning: "Magandang umaga po"
     - Afternoon: "Magandang hapon po"
     - Evening: "Magandang gabi po"
   - Include their name if provided

2. **Acknowledgment**
   - Thank them for reaching out
   - Reference their specific concern/question

3. **Main Response**
   - Answer their questions directly
   - Provide clear next steps if needed
   - Include relevant details

4. **Closing**
   - Professional sign-off
   - Contact information
   - Availability

### Templates:

#### For Inquiries:
```
[Greeting],

Salamat po sa inyong interest sa [product/service]! 

[Answer their specific questions]

[Next steps or call-to-action]

Kung may iba pa kayong katanungan, huwag po kayong mag-atubiling magtanong.

Best regards,
[Your Name]
[Contact Details]
```

#### For Follow-ups:
```
[Greeting],

Nag-follow up lang po ako regarding [topic].

[Brief context]
[What you need from them]

Salamat po sa inyong oras!

Best regards,
[Your Name]
```

## Examples

### Input:
"Customer is asking about delivery time to Mindanao"

### Output:
```
Magandang araw po!

Salamat po sa inyong tanong regarding delivery time. 

Para po sa Mindanao area, standard delivery time namin ay:
- Luzon: 3-5 business days
- Visayas: 5-7 business days  
- Mindanao: 7-10 business days

Pwede rin po namin i-arrange ang express delivery kung urgent. May additional fee lang po of ₱150-300 depending sa location.

Anong area po specifically kayo sa Mindanao? Para ma-give ko po ang exact timeline.

Salamat po!

Best regards,
[Your Name]
[Business Name]
📱 [Mobile Number]
```

## Notes
- Always double-check spelling of names
- Match the formality level of the sender
- When unsure, err on the side of being more formal
- Include relevant business info (operating hours, policies, etc.)
```

---

**2.3 - I-save ang File**

Press `Ctrl+S` (Windows) / `Cmd+S` (Mac)

✅ **Dapat ganito na ang folder mo:**
```
MyAgentSkills/
└── 📄 email-reply-skill.md
```

---

## Step 3: I-test ang Iyong Skill

### Para sa Claude Users:

**3.1 - I-load ang Skill**

Kung naka-setup na ang skills folder sa Claude:
1. Open Claude
2. Start new conversation
3. Type: "Use my email reply skill to respond to this: [paste email]"

**3.2 - Sample Test**

```
Test Input:
"Hi! Interested po ako sa pricing ng inyong virtual assistant services. 
May packages po ba kayo? Salamat!"

Expected Output:
Magandang araw po!

Salamat po sa inyong interest sa aming VA services!

Mayroon po kaming dalawang packages:

BASIC PACKAGE - ₱15,000/month
- 80 hours/month
- Email management
- Calendar scheduling
- Basic admin tasks

PREMIUM PACKAGE - ₱25,000/month  
- 160 hours/month
- Everything in Basic
- Social media management
- Customer service support

Pwede rin po namin i-customize ang package based sa inyong specific needs.

Gusto niyo po ba ng detailed proposal? Masasabi niyo rin po kung anong specific tasks ang kailangan niyo.

Salamat po!

Best regards,
[Your Name]
```

---

## Step 4: I-improve Base Sa Results

### 📊 Evaluation Checklist:

Pagkatapos ng test, check mo:

- [ ] ✅ Tama ba ang tone? (Professional pero friendly?)
- [ ] ✅ Complete ba ang information?
- [ ] ✅ Natural ba ang Taglish mix?
- [ ] ✅ May proper greeting at closing?
- [ ] ✅ Actionable ba ang response?

### 🔧 Common Improvements:

**Kung masyadong formal:**
```markdown
## Tone & Style:
- Professional pero approachable
- Use "po" sparingly, not in every sentence ← ADD THIS
- Conversational pero respectful ← ADD THIS
```

**Kung kulang ang details:**
```markdown
## Additional Info to Include:
- Operating hours
- Payment methods accepted
- Turnaround time
- Refund/cancellation policy
```

**Kung inconsistent ang style:**
```markdown
## Style Rules:
- Always use Filipino greeting
- Keep body in Taglish (50-50 mix)
- English for technical terms
- Filipino for personal touch
```

---

## Common Problems at Solusyon

### ❌ Problem 1: "Di gumagana ang skill"
**Solusyon:**
- Check if tama ang file format (`.md` dapat)
- Verify naka-save sa tamang folder
- I-restart ang AI assistant
- Check kung naka-point sa correct skills directory

---

### ❌ Problem 2: "Sobrang formal ng output"
**Solusyon:**
Add sa Instructions:
```markdown
### Tone Adjustment:
- Write like you're texting a professional friend
- Okay ang emojis if appropriate (😊 👍)
- Use "ka" instead of "kayo" for younger clients
```

---

### ❌ Problem 3: "Minsan English, minsan Tagalog"
**Solusyon:**
Be specific sa skill:
```markdown
### Language Rules:
- Greeting: Always Filipino
- Body: 60% Filipino, 40% English
- Technical terms: English (with Filipino explanation)
- Closing: Filipino
```

---

### ❌ Problem 4: "Too generic ang responses"
**Solusyon:**
Add examples section with specific scenarios:
```markdown
## Scenario-Specific Templates:

### Scenario: Product Out of Stock
[Template here]

### Scenario: Price Negotiation
[Template here]

### Scenario: Delivery Delay
[Template here]
```

---

## Real-World Examples Para sa Pinoy

### Example 1: Social Media Post Skill (Para sa Online Sellers)

```markdown
# Facebook Post Skill - Online Selling

## Description
Creates engaging Filipino-style Facebook posts for product selling

## When to Use
- New product launch
- Sale/promo announcement
- Customer testimonial post
- Product restock announcement

## Instructions

### Hook Formulas:
1. Question hook: "Sino dito ang [relatable situation]?"
2. Emoji hook: "🔥🔥🔥 [Product name] IS BACK!"
3. FOMO hook: "LAST 10 PIECES NA LANG!"
4. Social proof: "Bakit sold out agad? Dahil..."

### Post Structure:
- Hook (1 line)
- Problem/Need (2-3 lines)
- Solution/Product intro (3-4 lines)
- Benefits (bullet points)
- Call-to-action
- Price and ordering info
- Hashtags

### Tone:
- Conversational Taglish
- Enthusiastic pero hindi pushy
- Use emojis (✨💯🔥👌)
- Include social proof when possible

## Example Output:

Sino dito ang laging nauubusan ng oras dahil ang dami pang trabaho? 🙋‍♀️

Relate much sa pagod after work, tapos andaming kailangan pang gawin sa bahay? 

Good news! Our PREMIUM MEAL PREP CONTAINERS are back in stock! 🎉

✅ BPA-free and microwave-safe
✅ Leak-proof guarantee
✅ Perfect portion sizes (diet-friendly!)
✅ Stackable - tipid sa space
✅ Dishwasher safe

Meal prep on Sunday = hassle-free buong week! 💯

PROMO PRICE: ₱299 lang for set of 5!
(Regular price: ₱450)

ORDER NOW:
📱 Text "MEAL PREP" to 0917-XXX-XXXX
💬 DM us here
🛒 Shopee link in bio

Limited stocks lang! First come, first served! 🏃‍♀️

#MealPrep #HealthyLifestyle #FilipinoFoodie #BusyMomHacks
```

---

### Example 2: Client Proposal Skill (Para sa Freelancers)

```markdown
# Freelance Proposal Skill

## Description
Creates professional but personal proposals for Filipino freelancers

## When to Use
- New client inquiry
- Project bidding (Upwork, Onlinejobs.ph)
- Rate negotiation
- Service package presentation

## Instructions

### Proposal Structure:
1. **Warm Greeting**
   - Use their name
   - Reference their project specifically

2. **Understanding Section**
   - Show you read their requirements
   - Identify their pain points

3. **Your Solution**
   - How you'll solve their problem
   - Your approach/process
   - Timeline

4. **Why You?**
   - Relevant experience
   - Similar projects done
   - Your edge

5. **Investment**
   - Clear pricing
   - What's included
   - Payment terms

6. **Next Steps**
   - Call to action
   - Availability
   - Contact details

### Tone:
- Professional pero approachable
- Confident pero humble
- Solution-focused
- Use "we" to build partnership vibe

## Example Output:

Hi [Client Name]!

Nabasa ko po ang inyong post regarding [project name], and I'm really excited about this opportunity!

**What I Understand:**
You need [specific deliverable] na:
- [Requirement 1]
- [Requirement 2]
- [Requirement 3]

Plus, based sa timeline niyo, need niyo 'to by [date], tama po ba?

**How I Can Help:**
I specialize in [your expertise] and have worked on similar projects for [industry/type of clients]. 

My process:
1. [Step 1] - [Timeframe]
2. [Step 2] - [Timeframe]
3. [Step 3] - [Timeframe]

**Portfolio:**
[Link to relevant samples]
Recent similar project: [Brief description + result]

**Investment:**
Total Project Cost: ₱[Amount]

Included:
✅ [Deliverable 1]
✅ [Deliverable 2]
✅ 2 rounds of revisions
✅ Final files in [formats]
✅ Free support for [timeframe] after delivery

Payment: 50% upfront, 50% upon delivery

**Next Steps:**
Free po ako for a quick call this week to discuss the details. 

Available times:
- [Day/Time option 1]
- [Day/Time option 2]

Looking forward to working with you!

Best,
[Your Name]
[Portfolio Link]
[Contact Number]
```

---

### Example 3: Customer Service Skill (Para sa VA's)

```markdown
# Customer Service Response Skill

## Description
Handles common customer service scenarios with Filipino warmth

## When to Use
- Product complaints
- Delivery issues
- Refund requests
- General inquiries
- Negative feedback

## Instructions

### Response Framework (HEARD):
- **H**ear them out - Acknowledge concern
- **E**mpathize - Show understanding
- **A**pologize - If warranted
- **R**esolve - Offer solution
- **D**eliver - Follow through

### Tone:
- Empathetic and patient
- Solution-oriented
- Apologetic when needed pero not defensive
- Clear sa next steps

### Templates by Scenario:

#### SCENARIO: Late Delivery
```
Hi [Name]!

Pasensya na po sa delay ng delivery. I completely understand your frustration, lalo na kung matagal na kayong naghihintay.

Let me check this for you right away.

[After checking]

Here's what happened: [Brief honest explanation]

To make it right:
- [Solution/compensation]
- [Estimated new delivery date]
- [Added value if applicable]

I'll personally monitor this and send you updates every [timeframe].

Again, sorry po talaga for the inconvenience. Thank you for your patience!

[Your Name]
Customer Care Team
```

#### SCENARIO: Product Defect
```
Hi [Name],

Thank you for reaching out and sorry to hear about the issue with your [product].

I'd like to help resolve this immediately.

Could you send me:
1. Photo of the defect
2. Order number
3. Preferred resolution (replacement or refund)

Once I receive these, I'll process your [resolution] within 24 hours.

We really value your business and want to make this right po.

[Your Name]
```

## Notes:
- Never promise what you can't deliver
- Set realistic timelines
- Follow up proactively
- Escalate when needed
```

---

## 🎯 Assignment: Gawa ng Sarili Mong Skill!

Try creating a skill for YOUR specific work. Use this blank template:

```markdown
# [Skill Name]

## Description
[1-2 sentences: Ano ang purpose ng skill na 'to?]

## When to Use
[Bullet points: Kailan mo 'to gagamitin?]

## Instructions
[Step-by-step or guidelines]

## Examples
[At least 1 realistic example]

## Notes
[Special considerations or reminders]
```

---

## 📚 More Resources

- Main Guide: [Agent Skills Complete Guide](../README.md)
- Template Library: [/templates folder](../templates/)
- Community Examples: [/examples folder](../examples/)

---

## 💬 Need Help?

Join our community:
- **Facebook**: AI for Everyday Pinoys
- **Discord**: [Link]
- **Email**: [Your support email]

---

**Last Updated**: March 2026  
**Created by**: AI for Everyday Pinoys Community
