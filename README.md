
Hi [Team/All],

We’ve begun testing and completed an initial review of the graph interactions. Below are our key findings:
	1.	Swipe Gesture Behavior: While we are able to invoke the swipe gesture, it currently only triggers from the edge of the graph. Our expectation is for the gesture to be initiated from the center of the graph for a more intuitive user experience.
	2.	Vertical Swipe Interaction: We are not observing the vertical swipe interaction on the chart as previously demonstrated. Could you please confirm if this functionality has been implemented? (We’re sharing a sample interaction for reference — please note that the gesture starts from the center of the graph.)
	3.	Blank Screen Issue: Starting today, we’re intermittently seeing a blank screen on the chart. Please refer to the attached video for details.

Could we look into these items? I’m happy to connect over a call to walk through the issues, if that would be helpful.

Best regards,
Piyush

# calcualtorApp

Thanks for sharing the debuggable build.

Here’s a quick summary of what we found during our review:

Performance Testing: I ran performance checks using Instruments and didn’t notice any issues with the standalone build. However, since the SDK will be embedded within our existing app, there’s a possibility of performance impact during integration. We’ll need to keep an eye on this as we move forward.

Gesture Conflict: The attached video shows how the app currently handles swipe gestures. Based on our past experience, since we’re planning to use the web-based charts as a section within the existing app, there’s a likelihood of gesture conflicts between the native views and the WebView charts. Can you please share your thoughts on how we might handle or mitigate that?

Also, we noticed that the existing app uses TradingView for charts. Just wanted to confirm—will the final  product continue using TradingView, or is there a plan to switch chart providers?


[Manager's Name] possesses an exceptional understanding of both the technical and functional aspects of how the business operates, making him an invaluable leader within the team. He consistently sets clear expectations, providing guidance and structure that drive performance and success. His leadership skills are outstanding, fostering a supportive and productive environment. Additionally, [Manager's Name] maintains regular touchpoints, ensuring open communication and alignment on goals and progress. His ability to blend business acumen with technical expertise makes him a highly effective manager and mentor.

To further increase effectiveness, [Manager's Name] could focus on better aligning team members around the strategy for a program, ensuring everyone is on the same page and working towards a common goal.

While [Program Lead's Name] excels in domain expertise and leadership, there are areas where improvement is needed, particularly in teamwork. There have been instances where other teams have been blamed for delays, especially when stories weren’t fully groomed or communicated effectively. To mitigate this, [Program Lead's Name] should focus on improving documentation of technical discussions, ensuring that all teams are on the same page from the outset. Additionally, we have had to revise agreed-upon approaches late in the sprint, leading to significant rework. This could be prevented through clearer communication and documentation early in the process, which will reduce misalignment and enhance overall project efficiency.

[Program Lead's Name] is a highly knowledgeable program lead with deep expertise in the portfolio domain, making him an invaluable resource for the team. He demonstrates strong architecture design principles and is excellent at asking the right questions and contesting decisions when necessary to ensure optimal solutions. As a strategic partner with product and design, he contributes significantly to aligning vision and execution. [Program Lead's Name] is also very thorough in risk flagging, ensuring potential issues are addressed early, and he consistently upholds high standards for project delivery, both in terms of schedule and quality. His leadership skills foster a productive and collaborative environment, driving the team’s success.




[Developer's Name] is an exceptionally collaborative senior Android developer with amazing communication skills. She effectively engages with team members and stakeholders, fostering a positive working environment. During grooming sessions, she consistently asks the right questions, ensuring clarity and alignment on project requirements. When challenges arise, [Developer's Name] is proactive in raising the appropriate concerns with the right people, demonstrating her commitment to project success and team accountability. Her ability to navigate complex situations while maintaining open lines of communication makes her an invaluable asset to the team.

While [Developer's Name] excels in collaboration and communication, there are areas where she can enhance her impact. She should focus more on conducting thorough tech grooming sessions, ensuring that potential questions and concerns are addressed earlier in the sprint. By proactively identifying and resolving issues during grooming, she can significantly reduce the risk of rework and minimize challenges during delivery. This approach will not only streamline the development process but also enhance the overall quality of the deliverables. Emphasizing this aspect of her role will contribute to a more efficient workflow and greater project success.

[Developer's Name] is a highly collaborative senior iOS developer, known for being readily reachable and always willing to help with debugging and triaging issues. His active participation in grooming sessions and thoughtful questioning fosters a better understanding of project requirements and enhances team discussions. He possesses a keen eye for design, emphasizing that designs should be consistent at the component level, which is crucial for a seamless user experience. Additionally, [Developer's Name] plays a vital role in managing MR approvals and reviews, consistently providing meaningful feedback that improves the overall quality of the codebase. His contributions significantly enhance the team's effectiveness and product quality.

While [Developer's Name] excels in collaboration and design consistency, there are areas where he can further enhance his impact. He should focus more on driving grooming conversations, taking a proactive role in shaping discussions to ensure clarity and alignment on project goals. Additionally, he should take greater ownership of functional changes scoped by product and QA. By doing so, he can ensure that all aspects of the implementation are well understood and executed. Emphasizing these areas will not only strengthen his contributions but also help facilitate smoother project workflows and better team cohesion.



[QA Lead's Name] is a highly collaborative senior QA lead and the single point of contact for portfolio and trading QA, making him an invaluable resource for the team. He is always easy to reach and plays a critical role in debugging issues, ensuring timely resolutions. His thorough understanding of the SDLC enables him to effectively contribute to project delivery in a fully tested form. [QA Lead's Name] actively participates in grooming sessions, asking insightful questions that cover corner cases, which enhances the overall quality of our deliverables. Furthermore, he consistently focuses on automating test cases as new functionality is developed, improving efficiency and ensuring robust testing practices. His proactive approach and expertise significantly contribute to the team's success.


While [QA Lead's Name] demonstrates strong collaboration and expertise, there are areas for improvement. He should focus more on QA delivery, ensuring that timelines and quality standards are consistently met. Additionally, it’s important for him to remain calm in challenging situations; maintaining composure will enable clearer thinking and better decision-making when issues arise. Taking a step back to evaluate the situation can lead to more effective solutions. By enhancing his focus on these areas, [QA Lead's Name] can further strengthen his contributions and support the team's overall success.



While [QA Lead's Name] excels in collaboration, debugging, and test automation, there are areas where he can further improve. One key area is focusing more on testing preview stacks to catch potential issues earlier in the development cycle. Additionally, he should work on building more domain knowledge, which will help enhance the depth and quality of his testing. Finally, actively participating in both grooming and tech grooming sessions will ensure better alignment with the team’s goals and provide valuable insights into the features being developed. Focusing on these areas will strengthen his overall contributions to the project.

[QA Lead's Name] is an absolute rockstar in QA, consistently demonstrating exceptional collaboration and accessibility. He is always easy to reach and plays a crucial role in debugging issues, working closely with the team to resolve problems efficiently. His deep understanding of the SDLC ensures that every project is delivered on time and in a fully tested form, providing confidence in the product's quality. Additionally, he continuously enhances our testing processes by automating test cases as new functionality is built, improving the efficiency and effectiveness of our testing strategy. His proactive approach and technical expertise make him a vital asset to the team.

[Designer’s Name] is a highly collaborative team member who is always easy to reach and responds quickly. Her turnaround time for design feedback and iterations is impressive, enabling the team to maintain efficiency. She is very open to feedback and actively incorporates changes into her design components. Additionally, [Designer’s Name] consistently thinks of designs in terms of reusable components, ensuring consistency across different functionalities. This thoughtful approach not only enhances the user experience but also streamlines the design process, making her an invaluable asset to the team.


While [Designer’s Name] excels in collaboration and design consistency, there are areas where she can improve. She should focus more on ensuring platform parity between CW and mobile, particularly in maintaining information architecture consistency across platforms. Aligning the design structure will enhance the user experience. Additionally, she should work on better incorporating native gestures into her designs, ensuring they are compliant with Apple’s Human Interface Guidelines (HIG). This will help make her designs more intuitive and platform-appropriate, improving usability across different devices.

While [Designer’s Name] excels in collaboration and responsiveness, there are areas for growth. A key focus should be ensuring platform parity between CW and mobile, particularly in maintaining information architecture consistency. Aligning designs across these platforms will provide users with a more cohesive experience. Additionally, [Designer’s Name] should prioritize accommodating native gestures in designs, ensuring they adhere to Apple’s Human Interface Guidelines (HIG). Incorporating these platform-specific gestures will enhance usability and align with best practices, making the designs more intuitive and user-friendly.

[Designer’s Name] is a highly collaborative team member who is always easy to reach and responsive to requests. Her turnaround time for design feedback and iterations is consistently excellent, ensuring the team can maintain momentum and meet deadlines. She is also very open to feedback, demonstrating a willingness to adjust and improve design components as needed. This flexibility and openness make her a key asset in refining designs to meet both user and business needs. Her positive attitude and proactive communication further strengthen the team’s design process and overall success.



[Designer’s Name] has been a standout leader for the design team, consistently demonstrating openness to feedback and critique. His collaborative approach fosters a creative and inclusive environment where ideas can be freely shared and refined. He is also highly skilled in critiquing designs and components, offering thoughtful, constructive feedback that improves the overall quality of the work. [Designer’s Name] leads the design team with vision and creativity, producing innovative designs that align with both user needs and business goals. His ability to balance creativity with practicality makes him a key contributor to the success of the team.


While [Designer’s Name] leads the design team with creativity and openness, there are areas where he can further enhance his impact. One key area is ensuring platform parity between CW and web, particularly in maintaining information architecture consistency across platforms. Greater attention to detail in aligning designs across these environments will create a more seamless user experience. Additionally, [Designer’s Name] should focus on better accommodating native gestures in designs, ensuring they align with Apple’s Human Interface Guidelines (HIG). Incorporating these platform-specific gestures will improve usability and ensure designs meet industry standards.


[Employee's Name] has been an invaluable asset to the team, consistently demonstrating a high level of reachability and willingness to help. She is always ready to assist with pilot and production checkouts, ensuring smooth transitions and issue resolution. Her ability to write clear and detailed user stories is crucial in aligning the team's work with business needs. Additionally, she is proactive in triaging JIRA tickets, addressing issues efficiently, and ensuring nothing falls through the cracks. [Employee's Name] also excels in collaborating with both the design and engineering teams, fostering strong cross-functional partnerships that contribute to successful project outcomes. Her proactive and collaborative approach enhances team efficiency and project delivery.

While [Employee's Name] excels in many aspects of her role, there are areas where she can further improve. One key area is writing more thorough user stories, ensuring that all corner cases and edge scenarios are fully considered. This will help the team avoid ambiguity and potential rework. Additionally, [Employee's Name] would benefit from being more actively involved in tech grooming sessions and standup calls, where her presence can provide valuable insights and foster better alignment between product and engineering. By focusing on these areas, she can enhance her contributions to the team’s overall success.



[Developer's Name] has established himself as the foremost expert on the portfolio module, demonstrating exceptional domain experience and in-depth knowledge. He has proactively trained himself to understand every aspect of the portfolio functionality, becoming a key resource for the team. His ability to provide multiple approaches for solutions is commendable; he effectively outlines the pros and cons of each option while considering all corner cases and nuances. This thorough analysis not only aids in informed decision-making but also enhances the overall quality of our projects. [Developer's Name]'s expertise and strategic thinking significantly contribute to the team’s success and innovation in developing robust solutions.

While [Developer's Name] excels in his technical expertise, there are areas where he can enhance his impact. One key area is communication; improving how he shares updates and progress on projects will foster better collaboration with the team. Additionally, focusing on timely follow-ups will help ensure that all stakeholders remain informed and aligned on project statuses. Finally, he should prioritize reducing the turnaround time for solution fixes. Streamlining his approach to addressing issues will enhance efficiency and minimize delays. By working on these areas, [Developer's Name] can further strengthen his contributions and support the team's overall success.


[Developer's Name] has demonstrated valuable domain experience, particularly in trading and transfer functionality. His understanding of these critical areas significantly enhances our backend processes. He excels in teamwork, collaborating effectively with colleagues to achieve shared goals. Notably, his contribution to debugging issues has been instrumental; he approaches challenges with a solution-oriented mindset and consistently delivers quick turnaround times. This efficiency not only resolves problems swiftly but also minimizes disruption to ongoing projects. Overall, [Developer's Name]'s domain knowledge, teamwork, and operating effectiveness make him a key asset to the team.


While [Developer's Name] has shown strong skills in backend development, there are several areas where he can further enhance his effectiveness. One key focus should be on improving his architectural design solutions for backend APIs. By investing time in designing scalable and robust architectures, he can ensure long-term success and maintainability. Additionally, it’s crucial for him to adhere more closely to delivery timelines, as this will improve overall team efficiency and project flow. Finally, considering backward compatibility in his design choices will enhance user experience and ensure smooth transitions for existing users. Addressing these areas will strengthen his contributions and align better with team objectives.


Though I had limited time to work with [Developer's Name], it was clear he has a deep understanding of his analytics domain. In the brief period we collaborated on mobile analytics and tagging, he demonstrated solid expertise and effectively handled complex tasks. Additionally, [Developer's Name] has strong communication skills, clearly articulating his ideas and providing timely updates, which made collaboration smooth and efficient. His ability to explain technical details in a clear manner further ensured that everyone was aligned. His combination of expertise and communication makes him a valuable asset to the team.



While [Developer's Name] has demonstrated solid skills in analytics and communication, there are areas where he can enhance his impact. One key improvement is to focus on consistently optimizing the loading time and performance of Tableau dashboards. By proactively identifying and addressing performance bottlenecks, he can significantly improve user experience and overall efficiency. Engaging in regular performance reviews and seeking feedback from users can help him identify areas for enhancement. Additionally, staying updated on best practices for Tableau performance optimization will further strengthen his contributions to the team and ensure that the dashboards provide timely insights.




[Developer's Name] demonstrates strong potential, but she should work on developing a greater sense of ownership over her modules. Taking full responsibility for the end-to-end development process will enhance her impact. Additionally, she should actively participate in both product and technical grooming sessions, ensuring she fully grasps requirements and raises any concerns during functional grooming. Strengthening her engagement in these discussions will prevent issues later in the process. Furthermore, focusing on more thorough merge request (MR) reviews will help ensure higher-quality code and better alignment with team goals.

While [Developer's Name] shows potential as a mobile developer, he should focus on developing a stronger sense of ownership over his assigned modules. Greater accountability in overseeing a module’s end-to-end development will enhance his contributions. Additionally, he can improve by engaging more proactively in both product and technical grooming sessions, ensuring a better understanding of requirements and technical details early on. Finally, a more diligent approach to merge request (MR) reviews, with thorough attention to code quality and alignment with project goals, will help improve the overall output and efficiency of the team.




While [Developer's Name] consistently delivers strong results, there are opportunities for growth in thorough tech grooming. There have been instances where API contracts and expectations were revised post-delivery, which could have been addressed earlier with more detailed technical grooming sessions. By investing additional time in the planning phase—ensuring all technical aspects are thoroughly vetted and potential issues surfaced—[Developer's Name] can help prevent rework and maintain alignment across teams. Strengthening this aspect will further enhance product quality and reduce delays, allowing smoother project execution.


[Developer's Name] consistently excels in technical and functional expertise. As a rockstar developer, he possesses deep knowledge across multiple domains, enabling him to deliver high-quality solutions efficiently. His broad understanding of backend systems, coupled with his ability to remain calm and composed in challenging situations, sets him apart. When faced with critical issues, [Developer's Name] responds with quick turnarounds, providing clear, effective resolutions. His teamwork is equally commendable, always collaborating smoothly and supporting colleagues with timely assistance. His operational effectiveness and technical prowess make him an invaluable asset to the team.


