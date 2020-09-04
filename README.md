# BusinessQuantumFAQ
FAQ about the business side of quantum computing aimed at researchers in academia. 

**If you're here, you're absolutely welcome to contribute to this project. To do so, just create a pull request. You can contribute in various ways, including:**
- **Posing a new question**
- **Suggesting a resource**
- **Adding some short notes as an answer**
- **Expanding on an existing answer**
- **...**

This FAQ will focus on quantum computing (hardware & software) rather than broader quantum technologies (i.e. quantum sensing, quantum cryptography). While there are many interesting things to learn about the broader technologies, the business case for those is more obvious. When it comes to quantum computing, however, the business case is not so clear (at least to researchers in academia), given that the development of a useful fault-tolerant quantum computer might still be quite some time in the future. The purpose of this FAQ is to explain the business case for quantum computing, given this context, to researchers from an academic background. 

## Questions

#### Q: Why do we need a FAQ about the business side of quantum computing aimed at researchers in academia?

Right now, there are some academics who are thinking roughly like this:

- I know that quantum computers can solve some very specific problems, like factoring, more efficiently than classical computers.
- This is cool and all, but how world-changing is factoring anyway?
- And in any case, we will need around a million qubits to make a fault-tolerant quantum computer able to factor usefully large numbers.
- This is many years in the future, isn’t it?
- So what’s is going on? 
- Why would anyone who wants to make money invest in quantum computing?
- Why are all my friends leaving academia to go to industry?
- Are my friends tricking the investors to give them money when they shouldn’t? 
- Are the investors tricking my friends to some end that I don’t understand?
- Isn’t all of this hype dangerous to my _legitimate_ research program?

The point of this FAQ is to help answer these questions, either directly or indirectly.

### INVESTING

#### Q: What is a venture capital (VC) investor?

_Some clues on how to answer this question might be found in the links under "About VCs and their perspective" in the Suggested Resources section at the end of this document._

#### Q: What is deep tech?

_TBA_

#### Q: What are the stages of startup funding?

- Pre-Seed Funding: The bootstrapping stage
  - Friends, Family & Fools (FFF)
  - Business angels
  - Accelerators
- Seed Funding: Product development stage
- Seed Plus Funding: Bridge round
- Series A Funding: First round of VC
- Series B Funding: Second round of VC
- Series C Funding: Third round of VC
- Series D Funding: Special round of funding
- Initial Public Offering (IPO): Stock market launch

#### Q: What kind of investors exist in the QC ecosystem?

In most industries (and certainly in Deep Tech and thus QC) there is what is known as _specialization_ in funds. 

Right now, there is a very small handful of funds that invest in only QC. By doing so they are fully immersed in the industry and can provide additional value to the founder (networking, access to additional capital, access to advisors, grants, etc). 

On the other hand, big funds (that usually have at least one investment in their portfolio) enter with a purely financial strategy: either portfolio diversification that considers QC a higher risk-higher return asset, or for potential leverages within their investments.

The third case is corporate entrepreneurship. Big corporations are typically risk-averse and are very slow to adapt new technologies into their processes. Therefore, the best way for them to do so, is to create accelerators or small funds that are highly linked to their industry. From those vehicles they can spot trends, identify opportunities and identify key people, for only a fraction of what it would cost to do "in house". In many cases those investments hold a majority of the shares of the company and, when it makes sense, they end up buying the whole company and incorporating it into the home company.

#### Q: Why would someone invest in a quantum computing startup?

The reason behind investing in any company depends on various things. In most cases it’s about making a good return on the investment (ideally 20x onwards) <citation for 20x?>, but it also depends on the investment round, type of company, investment fund, and ultimately the person behind the investing.

In QC, we can divide the types of investment based on the capitalization needed:

- Hardware companies that require more starting capital will lure "big guns” investors, with wide portfolios, who are used to investment rounds with long horizons (series A, B or C). Examples are D-Wave [7] and IonQ [8].
- Software companies (either consulting or SaaS) are typically less capitalized and follow smaller rounds. As such, they can start with Seed rounds (or even "FFF", Friends Fools and Family), and grow from there.

Since Quantum Computing is a young field, the investing strategy differs from more developed and mature industries. The economics doesn’t lure dividend-based investors, so key performance indicators (KPIs) measuring a company's overall financial performance—such as earnings before interest, taxes, depreciation, and amortization (EBITDA) or annual recurring revenue (ARR)—won't be typically considered. In QC, investors typically find their returns on what is known as an “exit”.  They will be looking at intellectual property (IP), papers and patents, key people in the team, and client acquisition capabilities.

#### Q: What is an “exit”?

An “exit” is the point at which a VC sells their stake in a company to realize their gains (or losses). 

The main exits will be (usually a combination of):

- Bigger round exit (replacement), i.e. from Seed to Series A
- Merger with another QC company
- Acquihire - A corporate or a bigger animal buying your team, primarily for the skills and expertise of its staff, rather than for the products or services it supplies.
- Client acquisition - Buying your clients, contracts and partnerships
- IP acquisition - Buying your technology

The exit comes after a new round with replacement investors and new capital. This is what increases the company valuation (sometimes artificially). 

Sometimes, this leads to miss-management, or conflict of interests between founders and investors. The latter being more interested in increasing the valuation and going to a new round, the former into building a product that creates value. It is important to make sure that investors and founders are fully aligned on the short and long term plans for the company.

#### Q: Are VC investors foolishly funding some quantum startups that they shouldn’t be?

This partial answer was given by Scott Aaronson [6]:

"I don’t know the answer to this question (and don’t pretend to know when I’m asked). One problem is that many, many things that are easy to recognize as “foolish” in retrospect were hard to recognize as foolish at the time, even by the best experts that there were. Or the people who correctly said that these were foolish investments (and gave correct reasons), also said that Apple, Facebook, and Bitcoin were foolish investments.

One thing you learn, from even short exposure to the VC world, is that VCs are not even trying to answer the same question that an academic would: “is this proposal intellectually sound, or isn’t it?” They’re looking at a large number of other ways they might recoup the investment, like accumulating valuable IP, a buyout by a larger company (which might be more for the people than for the idea), etc. That makes it even more impossible for me to judge, except in some very special cases, whether people are making good or bad investments."

### BUSINESS

#### Q: Why are businesses interested in exploring quantum computing *now*?

Yianni Gamvros discusses the idea of _Quantum Insurance_ [1]:
- "You don’t want to get blindsided and find out from others what is possible. You should have a quantum strategy and contingency plans.
- If you wait for the technology to mature, it will be too late. You need to start training people that can hit the ground running as soon as the technology gets there. Training people takes time, literally years.
- Technology timeframes are always shrinking. Twenty years ago, people thought quantum computing was a sci-fi dream. Ten years ago, most people believed practical quantum computers were 50 years out. Today, we think they are three to five years away."

#### Q: Why are established companies (IBM, google, Amazon, Microsoft) intersted in building a quantum computer?

_TBA_

#### Q: What are the common business relationships?
- A non-quantum business seeks advice from a quantum business about whether quantum computers can solve any of their problems, e.g. a pharmaceutical company wants to know if a quantum chemistry algorithm can help with drug design. 
- A manufacturer provides a service to a quantum company to help develop their technology, e.g. a foundry makes the chips for a photonic quantum computing company. 

#### Q: There are many quantum software companies out there. How can I differentiate between them?

_TBA_

### TECHNICAL

#### Q: What are the different types of hardware? 

- Neutral Atoms
- Nitrogen Vacancy Centres in Diamond
- Photonic
- Spin in Silicon
- Superconducting
- Topological
- Trapped Ions

#### Q: How should I assess the performance of a quantum computing device?

It’s useful to consider the following points (as suggested by Scott Aaronson [4]):

- How many qubits does it have? (more is better)
- What are the qubit coherence times? (longer is better)
- What is the connectivity? (higher is likely better, but not always)
- What are the 1- and 2-qubit gate fidelities? (closer to 1 is better)
- What depth of circuit can you do? (higher is better)
- What resources do the standard classical algorithms need to simulate your system? 
- What’s the main drawback of the system, i.e., what spec is the worst/most needs to improve? 
- What prevents this architecture from being scalable right now? 

#### Q: Where can I get these performance parameters?

Some of these can be found on company websites. For others, you may need to read the press releases or journal articles announcing a specific device.

Many of these performance parameters are also summarised in several "scorecards" hosted on the Quantum Computing Report website [5], but a subscription is required to access these.  

#### Q: What is the difference between a noisy intermediate scale quantum (NISQ) device and a fault tolerant quantum computer?

### PERSONAL

#### Q: Why would a tenured professor leave their cushy university position to start a quantum computing company? 
- The opportunity to have real impact on technological progress [2]
- The potential to relive the early days of computing [2]

#### Q: How should I read the news in this area?
The amount of quantum tech news is growing rapidly. Reading everything is unsustainable and stressful, and makes you prone to overvaluing information you’ve spent a great amount of time consuming [3]. 

Most articles fall into one of these categories:
- New company 
- Company receives new funding 
- Company develops/releases new hardware
- Company improves hardware performance
- Company releases/updates software
- Company offers new professional services
- New consortium/partnership between players in industry and/or academia
- New educational initiative
- New funding available
- New roadmap/blueprint by government or other body 
- New academic research result that impacts the industry
- Industry gossip (e.g. X poached Y from Z)
- (any others?)

To figure out which ones to read:
1) Define your professional and personal goals.
2) Decide which of these categories will affect your goals.
3) Pay attention to the top few. 

For example, a professor with no interest in leaving academia might read only about funding initiatives bridging industry and academia, to be aware of relevant opportunities. 

A fresh graduate looking to enter the industry might read only the “about the company” sections of press releases, to get an idea of who the active players are. 

A job seeker preparing for an interview with a specific company might focus on articles about that part of the industry, and read them in some depth to have a good grasp of subtle differences between competitors. 

An industry professional might focus on articles discussing strategic partnerships and industry gossip. 

(These are just illustrative examples, so don’t follow them verbatim. Rather, define a strategy appropriate for you and your goals.)

Pro tip: many articles have sections explaining the basics of quantum information aimed at the general public. You can often skip these, especially if you have a background in the field. 

## References

- [1] https://thequantumdaily.com/2020/07/30/head-of-business-development-at-qc-ware-yianni-gamvros-reflects-on-the-present-and-future-of-quantum-computing/
- [2] http://nisqybusiness.com/2019/08/05/what-the-hell-have-i-just-done/
- [3] https://fs.blog/2018/04/first-principles/
- [4] https://www.scottaaronson.com/blog/?p=4649
- [5] https://quantumcomputingreport.com/scorecards/
- [6] https://www.scottaaronson.com/blog/?p=4447#comment-1827146
- [7] https://www.crunchbase.com/organization/d-wave-systems/company_financials
- [8] https://www.crunchbase.com/organization/ionq-inc/company_financials

## Suggested resources

For resources that could be relevant, but haven't been included in the main text yet. 

#### A series by Michael Biercuk after he shifted from academic to quantum tech company founder. 

- https://www.linkedin.com/pulse/opportunity-vs-truth-academic-founders-journey-michael-biercuk/
- https://www.linkedin.com/pulse/dont-afraid-academics-well-prepared-sales-michael-biercuk/
- https://www.linkedin.com/pulse/academics-bring-more-negotiation-table-than-expect-michael-biercuk/
- https://www.linkedin.com/pulse/magic-words-academic-founders-unencumbered-ip-michael-biercuk/
- https://www.linkedin.com/pulse/tips-vcs-better-engage-researchers-michael-biercuk/

#### About VCs and their perspective

- https://medium.com/swlh/what-i-wish-someone-had-told-me-about-venture-capitalists-9f2ed28c59b3
- https://www.youtube.com/watch?v=jOSXY8c88sc&feature=emb_logo (talk by Cristina Escoda)
- https://medium.com/mfv-partners/how-a-new-generation-of-computing-is-driving-disruptive-change-6e476f908c9a

#### About building the link between quantum computing technologies and VC requirements

- https://gumroad.com/perron/p/what-is-deep-tech
