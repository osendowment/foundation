# FAQ

### What is the Open Source Endowment (OSE)?
OSE is the world's first endowment fund dedicated to sustainably funding free open source software. It collects donations from the open source community, invests all of them into low-risk assets, and spends only the returns to support critical yet underfunded OSS globally. It was incorporated as a US nonprofit on February 14, 2025, and is pending 501(c)(3) status.

### Why does OSS need more sustainable funding?

**Open Source runs the modern world**: Over 95% of software codebases rely on OSS, with applications averaging 500+ OSS components. Like roads and bridges, OSS requires ongoing maintenance to fix bugs, address security issues, and adapt to changes. 86% of contributors are currently unpaid, and many critical projects lack resources, leading to notable incidents like [Heartbleed](https://en.wikipedia.org/wiki/Heartbleed) (2014) and [Log4Shell](https://en.wikipedia.org/wiki/Log4Shell) (2021).

**Current funding models are not enough**: There are many funding sources for FOSS: corporate budgets, OSS nonprofit foundations, tools like GitHub Sponsors, a few government programs, etc. However, none of them simultaneosly combine the following three features OSE is designed around: 

- **Sustainable funding**: Stable, long-term cash flow for OSS, not tied to annual donations, volatile corporate or governmental budgets.
- **Systemic focus**: Targets critical underfunded OSS, prioritizing the "long tail" instead of popular, large or specific supply chains.
- **Scalability and efficiency**: Uses a transparent, digital-first approach to attract funding from the tech industry and choose grantees, that can attact more donors in the future. 

The current solutions are already making impact, and OSE as a complementary tool to them. By filling in the gaps in the current OSS funding landscape, OSE aims to reduce the risks for the global software supply chain we all rely on.

## Donations & Governance

### How to donate to OSE?

People and organizations are welcome to donate at https://endowment.dev/#donate. All individuals who do this before the public launch of OSE will be credited as founding donors and get additional governing rights in case of $1000+/year donation (OSE membership).

### Why does OSE accept only individuals as founding donors?

OSE is built as a community-driven nonprofit with inclusive governance based on individual donors — people with passion to OSS and "skin in the game". The endownent model makes sense on a 20-year+ planning horizon, and most organizations plan for shorted periods.

### Does OSE accept corporate and other institutional donors?

Yes! Such donors are very welcome, and we are happy to collaborate with companies and foundations caring about Open Source. Meanwhile, we do not offer them any governing rights to preserve the long-term neutrality and alignment with the global OSS community. 

### What will OSE governance look like in the long-term?

We aim to build a self-governing endowment foundation, that is managed by a diverse community of individuals (OSE members), who care about Open Source and have personally donated to the endowment fund. They will gradually gain more power over electing board members. Meanwhile, the board should be focused on building scalable systems - if successeful, the OSE will work efficiently while its board and management won't eventually have much to do except for monitoring. 

## Investments

### How are donated funds invested?

While OSE is waiting for the 501(c)(3) status approval in the US, all donations are invested in US Treasury Bonds (5% yield, very low risk). After the approval, we plan to start working with a pre-selected US licensed asset manager focused on nonprofits (target yield ~ 7-8%). 

### How is investment income spent?

All expected investment income from donations to the endowment is spent on grants to the OSS projects. The target spend rate is 5% of the endowment fund per year. The first grants are expected to be distributed around Q1 2026.

## Grants

### What principles guide OSE's grantmaking?

OSE aims to ensure sustainable maintenance of most critical OSS projects, reducing risks to the global software supply chain by addressing funding gaps. Our key principles:

- **Long-term impact**: Priority to fixing underlying issues (e.g. maintainer burnout) instead of fighting with their surface-level consequences (e.g. vulnerabilities). There are already enough organizations doing "firefighting" in the global village of open source, and OSE's role is more about funding the preventive installation of "fire safety measures" in the most critical buildings.
- **Follow the market**: OSE is not opinionated about which software is more valuable and worthy of support, and bases its neutral judgment on the internal estimation of how the world consumes OSS. Such an approach will account for the full dependency tree and naturally prioritizes low-level infrastructure libraries (e.g. C/C++) over more app-focused ecosystems (e.g. JS/TS).
- **Measurable and transparent**: Algorithmic (but not automatic!) data-driven selection of grantees, based on the model co-developed with the OSE donors, which has human-in-the-loop elements. It will be open to the OSE members, and partially to the public. 

### How will the selection model look like?

OSE is currently developing the selection model and planning to release its first version in Q1 2026. It will use the scoring approach based on the estimated value and risk for top OSS projects. Here are their potential components:

- **Value for the ecosystem**
	- Dependencies
	- Downloads
	- Potential losses if removed from the global tree
	- Endorsements from OSE donors, OSS foundations, etc.
- **Risk of the project**
	- Complexity: LOCs, etc.
	- Maintainers: active maintainers, bus factor, MTTR for issues, etc.
	- Security: OpenSSF score, CVEs, etc. 
	- Funding: GitHub Sponsors, known funding, etc.

The selection model will consist of several steps: a data-driven approach will be used for initial targeting, and human-in-the-loop elements will be required at the due diligence stage, for instance, to check if the project is already well-funded. Public materials on the model are published in our [repo](https://github.com/osendowment/model).

### Does OSE support OSS projects which have a related tech business?

If an open source project can turn into a sustainable business, it probably should. Meanwhile, OSE supports only nonprofit projects, excluding OSS startups and corporate projects from its scope.

### What are grants provided for?

There are two ways we currently think about awarding grants:

- **Forward-looking**: Maintainers of the project should use grants to perform a measurable chunk of work, which will de-risk the project.
- **Backward-looking**: Some maintainers have already been working on their projects for decades without any reasonable support. We publicly acknowledge and provide monetary gratitude for what they have done, decreasing potential burnout.

The impact of grants is planned to be checked quantitatively (data-driven metrics) and qualitatively (check-in calls). We also aim to highlight the critical maintainers, so everybody could join OSE in supporting them.

## Other questions

### Can [Goodhart's law](https://en.wikipedia.org/wiki/Goodhart%27s_law) cause any scaling problems?

In the short term, there is no such problem at all. As for the long term, the tech industry has been capable of building robust systems with automated inputs which can't be gamed well — like Google search, YouTube and all large social networks, including GitHub. The selection model can't be perfect, but we aim to make it openly developed, and "with enough eyeballs all bugs are shallow".

### Why did nobody build an OSS endowment before OSE?

- **Endowment model requires a 20+ year planning horizon**: Most organizations, including charities, focus on quick wins and annual budgets. They can't afford to spend only ~5% of donations every year. Established charities can hardly launch next-gen initiatives — like many large or legacy organizations. Even in the case of OSS-enlightened leaders, governments would have a hard time explaining OSS to voters. Companies usually do not create endowments as their business priorities change over time. They are created by passionate individuals.
- **Endowment model fits well only targets with unlimited lifespans**: Most OSS communities are typically centered around targets with limited lifespans: software (like Linux), languages (like Python), and people. Software evolves and becomes obsolete over time, rendering any project-specific funding eventually irrelevant. Unlike any particular OSS ecosystem, OSS-at-large is an open-ended target.
- **OSS endowment requires a rare intersection of multiple areas of expertise**: This work requires experience in open source and dev-focused products, endowments, scaling of tech startups, fundraising etc. It requires leaders with a strong desire and ability to pursue their own personal non-profit initiatives. Most OSS people are not familiar with the endowment model, especially outside the USA/UK (majority). Most philanthropists are not familiar with open source values and their challenges — this problem did not exist 25 years ago.

### Are discussions regarding OSE open to the public?

Transparency is a foundational value of OSE, as a community-driven nonprofit project. Currently most OSE-related discussions and key documents are available for the OSE members and advisors at our [private repo](https://github.com/osendowment/foundation), which will become fully open at the public launch (after 501(c)(3) status approval). We already have a few public GitHub repos available for contributing, and plan to publish more in the future.

### How can OSE evolve in the long-term, especially in the AI-powered world?

We suppose that open source software will still be the cornerstone of the global tech infrastructure even in 50 years from now, as besides being a rapidly evolving code-generating component it is also a globally-decentralized cultural and social phenomenon. It is already everywhere and the entropy of the tech infrastructure will only increase. So there will be a need to sustainably fund its maintenance. In the long term, the share of AI agents performing open source maintenance will increase, so the OSE can achieve its targets faster than planned – some of the funds previously granted to people will instead go towards AI computing costs.

### Does OSE somehow relate to blockchain technologies?
From a governance design perspective, OSE's principles resemble DAOs: transparent, decentralized, skin in the game, etc. However, OSE is a usual regulated US nonprofit corporation and not a crypto org by any means. We will accept crypto donations (with proper KYC) in the future, but it is not a priority.

### How will OSE work with existing OSS-focused non-profits?

We design OSE as a next-gen solution for the old OSS problem, which attracts most donations from a new category of donors (tech individuals) and thus increases funding of the global open source ecosystem. It complements existing OSS foundations, without competing for resources.
