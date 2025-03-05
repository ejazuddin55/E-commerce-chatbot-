

Problem Statement
Every year, millions are spent by ecommerce companies on customer service. They want a reliable solution through which they could potentially save that money and resources and invest them elsewhere.
Online retail businesses face challenges in managing customer support effectively. It drains resources, both in terms of budget and human capital, which could otherwise be invested in business growth. 
Ecommerce businesses can focus on more complex problems but using AI for their own advantage.
However, many ecommerce businesses seems to have traditional means of resolving customer problems and queries which is through leveraging human resource for customer service.
Solution
With the rapid growth of e-commerce, businesses are facing an increasing volume of customer inquiries. These inquiries often relate to product information, shipping status, order details, and other relevant topics. Answering these inquiries promptly and accurately is crucial for maintaining customer satisfaction and loyalty. However, relying solely on human customer service agents to manage this workload can be inefficient and expensive.
To address this challenge, there is a growing need for automated solutions such as chatbots and virtual assistants. These tools can handle a large volume of repetitive inquiries, providing customers with quick and accurate responses. Chatbots can be programmed to answer frequently asked questions (FAQs), provide product information, track shipping status, and even resolve simple issues. 
By automating these routine tasks, chatbots free up human customer service agents to focus on more complex issues that require their expertise and empathy. This can lead to a more efficient and effective customer service operation, with improved customer satisfaction and reduced costs.
Targeted Audience/Users
Customers who have queries related to the any domain of a specific ecommerce website.
Customer who want to track their order status.
Ecommerce business managers/stakeholders.
Product owners.


Business Benefits
By automating routine inquiries, businesses can reduce support costs. Juniper Research predicts that chatbots will help businesses save over $8 billion annually.
Chatbots can provide instant responses, improving customer satisfaction. Salesforce found that 64% of consumers expect real-time assistance.
Maximum Availability for the customers. According to HubSpot, 82% of customers expect an immediate response to their inquiries.
Industry Data and Analysis
The global ecommerce chatbot market is expected to grow from $4.7 billion in 2022 to $15.5 billion in 2028, exhibiting a CAGR of 23.3%. [1]
Chatbots expected to cut business costs by $8 billion by 2022. [2]
82% of businesses believe that chatbots will play an important role in customer service within the next five years. [3]
The study published by an analysis firm called Juniper Research suggests that between three-quarters and 90 percent of queries in health care, banking, business areas will be dealt with by “chatbots” within the next five years, resulting in cost savings of up to $0.70 per interaction. [4]

These statistics demonstrate the rapid growth and increasing importance of ecommerce chatbots. Ecommerce businesses that are not already using chatbots should consider doing so to improve their customer service, increase sales, and reduce costs.
Guiding Principles behind solution
Provide quick and accurate answers to customer queries.
Provide real-time customer service 24/7.
The cost of operating and maintaining an ecommerce chatbot is significantly affordable for a business.
Provides high customization and flexibility for users and the business. 
Provides seamless and efficient customer service.



![image](https://github.com/user-attachments/assets/661cc3eb-531d-48c9-bd91-9b00455d9a1f)


Customer Journey:
![image](https://github.com/user-attachments/assets/07b1606d-9462-4de8-9c51-2a8507676222)


Architecture Diagram:

References:

[1]The global ecommerce chatbot market is expected to grow from $4.7 billion in 2022 to $15.5 billion... [online] Chatbot Market Size, Share & Trends Report. 
Available at: <https://www.marketsandmarkets.com/Market-Reports/chatbot-market-72302363.html> [Accessed 9 November 2023].

[2]CNBC 2017/05/09/ report on chatbots and their trends. [online] CNBC market research. Available at: <https://www.cnbc.com/2017/05/09/chatbots-expected-to-cut-business-costs-by-8-billion-by-2022.html> [Accessed 9 November 2023].

[3]STAMFORD, Conn. July 27, 2022. [online] Gartner Press Release. Available at: <https://www.gartner.com/en/newsroom/press-releases/2022-07-27-gartner-predicts-chatbots-will-become-a-primary-customer-service-channel-within-five-years> [Accessed 9 November 2023].

[4]STAMFORD, Conn. July 27, 2022. [online] Gartner Press Release. Available at: < https://www.cnbc.com/2017/05/09/chatbots-expected-to-cut-business-costs-by-8-billion-by-2022.html> [Accessed 9 November 2023].

Appendix A (Code for Dataset)

From the start of the development of this project, the unavailability of the dataset related to customer orders and their logistic information was a big challenge and so to counter that challenge, we synthesized our own dataset for our model. We created two files; one is a csv file which contains customer order information with order status and logistics info. The second file is a pdf file which contains FAQs and other information about the ecommerce website and business that our LLM can use to answer user questions. We individually created embeddings of each of these files and later merged them to store in our vector database. 






