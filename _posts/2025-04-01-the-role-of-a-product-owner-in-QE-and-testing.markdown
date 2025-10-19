---
title: The role of a product owner in Quality Engineering and testing
date: 2025-04-01 00:00:00 +0100
categories: [Quality Engineering]
tags: skills agile productowner qualityengineering excellence learning   # TAG names should always be lowercase
image:
    path: /assets/img/rolepo.png
---

In an earlier blog post [Boyd Kronenberg](https://www.linkedin.com/in/boydkronenberg/){:target="_blank"} and I wrote about "[How testing aligns with Quality Engineering](/posts/how-testing-aligns-with-quality-engineering){:target="_blank"}". This blog post is written in collaboration with [Niek van Malsen](https://www.linkedin.com/in/niekvanmalsen/){:target="_blank"}, Subject Matter Expert in Transformation Coaching. This blog post highlights the critical role of Product Owners in Quality and Testing.

### The Product Owner role
The Product Owner (PO) is responsible for maximizing the value of the product and the work of the Development Team. Their main responsibilities are:

- Visionary Leader: defines and communicates the product vision and strategy to ensure alignment with business goals.
- Key decision-maker: Balances stakeholder needs and technical constraints
- Backlog Management: Prioritizes and refines the product backlog based on value, dependencies, and risk.
- Stakeholder Collaboration: Engages with stakeholders to gather requirements, provide updates, and ensure continuous feedback.
- Quality: The delivered product meets quality standards and customer expectations.
- Adaptability: Continuously adapts to changes and new insights to mitigate risks and improve the product.

![Magic](/assets/img/Test-Automation.webp){: width="300" .right}
Recently there was a survey on [LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:7292666987741130753){:target="_blank"} on who is responsible for Quality. Although the team is responsible for doing the work, the PO is responsible for the product quality, since they decide about what work needs to be done and what the priorities are. POs play a vital role in building quality products. To be able to explain this well, let’s first look at how software development works.

### Software development in the VUCA world
Software development must deal with the VUCA world:
- Volatility: The dynamic rate of changes requires continuous adaptation and innovation
- Uncertainty: The unpredictability of events and issues in software development necessitates flexible planning and risk management
- Complexity: The complexity of interdependent systems and components require a holistic approach to problem-solving and a deep understanding of the IT landscape
- Ambiguity: The difficulty in accurately assessing reality in a complex and volatile landscape means that DevOps teams must be prepared to handle ambiguity and make informed decisions

VUCA highlights the need for (DevOps) teams to be agile, adaptable, and resilient in the face of rapid changes, unpredictability, complexity, ambiguity, confusion, new insights, and half answers. As a result, we face considerable risks. It underscores the importance of continuous learning, collaboration, and effective risk management to navigate the challenges and deliver quality software. We deal with users and clients who do not know exactly what they want or cannot explain it well. With IT teams that do not always understand the business well. How do we deal with these risks?

### Software development is about value and risks
As a team, gaining insight into value and risks requires a detailed understanding of the workflows, the product, and the risks surrounding it. Teams collaborate to solve problems that threaten the value of the product or the timely, successful completion of the work.

Risk-based thinking involves organizing the software development process around suspected risks. This means conducting risk analyses continuously and creating a Quality Strategy for the entire software delivery process. Risk-based thinking is a powerful approach to mitigating risks and delivering quality. Besides providing insight into risks, it also deepens understanding of the product and promotes “common or shared understanding.” This shared understanding helps reduce misunderstandings, improve effectiveness (and efficiency in the long run), and deliver quality outcomes. It is essential for effective collaboration and successful project delivery. According to the [State of Teams research conducted by Atlassian](https://www.atlassian.com/blog/leadership/shared-understanding){:target="_blank"} in 2023, teams with shared understanding better meet stakeholders’ expectations, use resources efficiently, develop new ideas, take pride and find a sense of purpose in their work, and experience increased motivation, energy, and enthusiasm.

### The role of a PO in the VUCA world
POs are the ones responsible for backlog management. They must ensure the team achieves a shared understanding of the work items. Unfortunately, many refinements are too short, poorly prepared and have insufficient outcomes like vague requirements, missing acceptance criteria and team members not fully understanding what the epic/feature/story is about. Feeling pressured to deliver, teams do not take enough time to learn. Eventually this will slow them down by delivering lower quality. Our experience is that the team members often feel pressured to deliver and do not speak up when they do not fully understand what is expected from them. We also see POs focus on delivering features too fast. They push to do efficient and fast refinement, which often means going through stories as fast as possible. Instead of focusing on sustainable quality, which in the long run is cheaper, faster and leads to more business value and happier customers and stronger teams. Remember that deep learning takes time: so, start promoting practices like discussing risks, asking more questions, visualizing where possible and creating acceptance criteria.

### Some good practices which POs can advocate
Reducing Work in Progress (WIP) and slicing stories as much as possible
Essential practices for maintaining a sustainable pace and delivering quality software. WIP limits help teams avoid overload, ensuring tasks are completed effectively by preventing bottlenecks, reducing context switching, and shortening lead times. Small stories enable teams to manage risk and receive quick feedback. According to the [State of DevOps report from 2024](https://dora.dev/research/2024/dora-report/){:target="_blank"}, this practice helps teams break down larger tasks into smaller, manageable pieces, allowing for more efficient and effective development. These practices help teams deliver incremental value, reduce complexity, and improve their ability to respond to changes.

### Risks analysis
Conducting risk analysis is crucial for teams to identify what needs action and to deepen their understanding of the product. Building quality software requires both solution-oriented and problem-oriented thinking. While most team members adopt an optimistic mindset, asking questions like “How should this work?”, testers often take on a pessimistic mindset, asking “What if X happens?”. Both mindsets are essential for developing quality software.

Discussing risks within the team leads to better software by exposing the most significant pitfalls. Savvy POs engage in risk discussions with the team to enhance their understanding of the product and the necessary activities for delivery. This helps prioritize quality measures effectively. However, this approach may extend the refinement process which is worthwhile because learning takes time.

### Feedback loops wherever possible
Teams should implement as many feedback loops as possible. While this may initially seem inefficient, it will significantly speed up teams over time. It enables teams to continuously improve the product and/or themselves. Common scrum ceremonies are valuable feedback loops, but there are many more: refinements to ensure the team understands what to build, clean coding: code reviews, pull requests, static code analysis, sufficient unit tests in development pipelines, continuous integration to check if the code merges without issues in pipelines with automated regression checks at various levels, testing, and monitoring.

Unfortunately, Product Owners (POs) are often not involved in developers’ workflows, which is a mistake. Technical debt results from choosing quicker delivery over clean code and thorough testing, leading to additional rework and maintenance challenges in the future. POs are often unaware of the time and costs involved in fixing the issues caused by shortcuts. An excellent PO will consider the risks and costs associated with repairing technical debt before taking shortcuts. They know costs are always higher than expected.

### POs are heavily involved in testing
In many teams, testers are responsible for deciding if the product can be shipped. Once the tests are completed, the story is marked as “done,” and the product is ready for shipment. However, it should be the PO making this decision. POs should ask the team to report on three key topics: how the product is performing, what kind of testing was conducted to determine this, and what the remaining risks are in the product and the process. This is known as the Testing Story. With this information, the PO can decide whether the product can be shipped.

Discussing testing with the PO helps the team highlight risks and challenges in testing. The PO can then help improve testability for more effective and faster testing or accept the risks involved and proceed by going slower. The responsibility of determining “how much testing is enough” should be a collaborative discussion between the team and the PO. Testers often tend to over-test, so reporting on the risks and the testing done helps the team perform the best possible testing, which is just enough testing.

### Make learning part of the way of working
Better refinements are crucial for fostering common understanding, but the PO can do even more to cultivate a learning culture within the team. Here are some ideas to help the team:

Collaborate with the team to create visual overviews of the product from various perspectives, such as architectural models, process diagrams, business model canvas, flow charts, and mind maps. This helps the team gain a comprehensive understanding of the product. Encourage the team to experiment where appropriate, fostering innovation and learning. Promote feedback loops, retrospectives, and reflection sessions to continuously improve processes. Help the team visualize the value stream, allowing them to identify and pick up improvement stories. Also practices like TDD and BDD help teams learn and create understanding across the team. Finally, proactively collect customer feedback to ensure the product meets users’ needs and delivers the right value.

By implementing these strategies, the PO can significantly enhance the team’s ability to learn, adapt, and deliver high-quality software.

### Mandating quality
Mandating quality is essential for successful software development. Ensure your team actively uses the Definition of Ready to verify they are prepared to start the work and the Definition of Done to confirm that all anticipated tasks are truly completed. Foster a learning environment by making the team a safe space where mistakes are seen as opportunities for growth rather than reasons for blame. In VUCA environments, mistakes are inevitable. Encourage Root Cause Analysis and blameless postmortems when significant bugs are found to help the team learn and prevent future errors. Advocate for code quality and support refactoring, testing, and automation when necessary.

### Wrapping up
Our clients demand faster, cheaper, and more predictable software delivery. The key to achieving this lies in adopting a “building quality in” mindset. This approach ultimately leads to faster, more cost-effective development, resulting in satisfied clients and happy teams.

POs play a crucial role in Quality Engineering by promoting quality products through effective collaboration. They should encourage risk analysis to help teams gain a deep understanding of the product and identify major pitfalls, leading to better software development and just enough testing. Additionally, POs should ask the team to report on the product’s status, the testing conducted, and the remaining risks. This information enables informed decisions about product shipment, potential process improvements, and enhanced testability.

By fostering a culture of quality and continuous improvement, we can exceed our clients’ expectations and deliver exceptional software products.

