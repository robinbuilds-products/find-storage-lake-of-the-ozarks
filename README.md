# Find Storage at the Lake of the Ozarks

**The first hyperlocal, AI-powered lead source for boat and RV storage at the Lake of the Ozarks, Missouri.**

🔗 **[Visit the live site](https://findstoragelakeoftheozarks.com)**

![Status](https://img.shields.io/badge/Status-Live_MVP-success)
![Build Time](https://img.shields.io/badge/Build_Time-15_Days-blue)
![Stack](https://img.shields.io/badge/Stack-Lovable_%7C_Claude_%7C_PostHog-purple)

---

## Why I built it

I kept seeing the same frustration at the lake: people couldn't find the right storage, and storage owners couldn't reach them.

After years building products inside a regulated global bank, I also wanted to test something. How fast can one product builder go from discovery to a live product, using only AI-native tools and no enterprise review layers, while still applying bank-grade privacy, risk, and accessibility standards from day one?

---

## The problem

Storage information at the lake is scattered. Owners and renters struggle to find each other, and the right kind of storage.

- National storage marketplaces exist, but none focus on this region: from Jefferson City over to Warsaw, down to Branson, Missouri, and every small town in between
- The lake is a small year-round community that swells with millions of visitors each summer, and renters come from all over the Midwest
- Many locals are older and less tech-focused, and many businesses still rely on phone calls to bring in customers
- Storage owners need to reach 80–90% capacity year-round. Without steady renters, some can't stay in business and have to sell

---

## What I built

- **Two-sided marketplace:** one side for renters searching for storage, one for the storage owners who need them
- **Plain-language AI search:** renters describe what they need in their own words, instead of fighting rigid filters
- **Regional listings:** 300+ listings scraped from the web, then human-verified and enriched. I expected 50 or 60
- **AI agents:** manage listings and generate content
- **AI search visibility:** opened to AI agents, aiming for assistants like ChatGPT and Claude to surface it over competitors. Content written by Lovable and Claude also brings in free SEO
- **Privacy and accessibility from day one:** bank-grade privacy, risk, and accessibility standards, with Termly handling privacy and legal pages

---

## Tech stack and decisions

| Tool | What it does | Why I chose it |
| :--- | :--- | :--- |
| **Lovable** | App builder and database | One source of truth and one place to make updates, after moving off Supabase |
| **Claude** | Thinking partner and content | Product thinking, planning, and SEO content |
| **PostHog** | Analytics | To learn how a less tech-focused audience actually uses the site |
| **Termly** | Privacy and legal | Privacy policy and legal pages in place from launch |
| **Notion** | Backlog | Worked as my Jira board |
| **Stripe** *(planned)* | Payments | Simple to plug in, and a US-based company |

### Key trade-offs

- **Dropped headless CMS:** Sanity didn't work correctly with Lovable, so content is written by Claude or Lovable and added directly in Lovable
- **Moved the database:** from Supabase to Lovable, so every update happens in one place
- **Smaller prompts:** big, all-in-one prompts burned through build credits and piled up tech debt, so I switched to small, focused changes

---

## Traction and status

- **Time to launch:** 15 days, solo
- **Listings:** 300+, human-verified
- **Early usage:** 300+ user sessions
- **Status:** live MVP. The build is on pause while I focus on my job search, with more updates planned

---

## Roadmap

**Goal:** fully working by the end of spring 2027, with time for users to test new features.

- **Verified owner sign-in:** so only real owners can claim and manage a listing
- **Owner lead dashboard:** one place to see all leads and inquiries
- **AI voice outreach:** since many local owners run their business by phone
- **Phone vs. email:** learn which owners respond best by phone and which by email
- **Renter marketing:** spend to bring renters to the site and drive inquiries
- **Owner subscriptions:** monthly and annual plans through Stripe, with pricing in the works

---

## What I learned

- Bank vs. AI-native: without enterprise review layers, I went from idea to live site in 15 days. Applying bank-grade standards solo took real effort, but it got done
- Clear user requirements still matter, especially when building toward an outcome instead of a feature
- Starting with the outcome kept me on track and helped me avoid scope creep from extra AI-suggested ideas
- Solo or with a team, you still need a backlog
- Opening the site to AI agents felt risky, but it taught me how AI search works
- It gave me room to explore AI-written content and building accessibility into the product
- I can take a product from idea to live on my own

---

**Built by [Robin O'Shaughnessy](https://www.linkedin.com/in/orobin/)**
