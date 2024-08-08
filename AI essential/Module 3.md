# Module 3

# **Prompts for different purposes**

## **Use cases**

As you explored previously, you might use an LLM at work to help boost your productivity and creativity and complete any of these useful tasks:

- Content creation
- Summarization
- Classification
- Extraction
- Translation
- Editing
- Problem-solving

**Note:** The following examples illustrate best practices; they aren’t exact templates to copy for every situation. Your results will vary based on a number of factors, including the specific LLM you’re using. Remember to critically evaluate all LLM output and to iterate on your initial prompt to get the most useful output.

In general, here’s how to make your prompts more effective:

- **Consider what you want the LLM to produce**. The LLM will generate more useful output when you include a specific instruction in your prompt, like *create*, *summarize*, *classify*, *extract*, *translate*, *edit*, or *solve*.
- **Provide necessary context.** The LLM will generate more useful output when you include detailed instructions, with specific guidance about the style or format of the output you want.

Up next, you’ll examine each of the use cases described earlier by considering an additional example for each.

![https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/AYa_4mjQQm-JWJr4v9B6CA_7fe992db0b1f4598a619ebec46e807f1_AI-Readings_Graphics_R-011_2.png?expiry=1717718400000&hmac=jHD3fv6_zqtHIYpLK1_5pYnsdZIMkA-zbKgGOA2ncrE](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/AYa_4mjQQm-JWJr4v9B6CA_7fe992db0b1f4598a619ebec46e807f1_AI-Readings_Graphics_R-011_2.png?expiry=1717718400000&hmac=jHD3fv6_zqtHIYpLK1_5pYnsdZIMkA-zbKgGOA2ncrE)

### **Content creation**

No matter your industry, an LLM can help you create content for a variety of purposes, such as blog posts, reports, product descriptions, and taglines. For example, suppose you’re working on an ad campaign for a new line of home appliances. You can ask an LLM to help you create an engaging tagline for one of the products:

*Act like you are a creative advertising professional who can apply innovative thinking to develop original taglines that project the positive qualities of a product. Create a concise tagline for a washing machine that gets clothes extra clean, has 25 settings, and fits in a small space*.

The prompt begins by describing the LLM’s role as a creative advertising executive. Next, the prompt clearly states that the task is to create a concise tagline for a washing machine. Finally, the prompt specifies the product features to include in the tagline.

**Pro tip:** Assign the LLM a role, job, or function to reinforce the purpose of the prompt and help guide the LLM to produce useful output.

### **Summarization**

An LLM can help you summarize many types of texts: reports, customer surveys, meeting notes, emails, and more. For example, the following prompt asks an LLM to provide a summary of a lengthy email:

*The following text is an email from a software vendor. Summarize its main points in a bulleted list:*

*"I hope this finds you well. It was a pleasure to chat with you at the conference last week.*

*Following up with more detail on our pricing plans. Our bronze level subscription gets you access to three of our most popular software products as well as training videos for these products. If you have additional software needs, you can subscribe at the silver level. This level allows you to choose two additional software products, with training videos on those products, as well as gets you 24-hour support on any difficulties you encounter while using the products. Finally, our gold level membership gets you access to all ten of our software products. You get training for all ten products as well as 24-hour support, and you are also the first to enjoy any beta additions to our products.*

*Please contact me for the pricing of the level that interests you. We offer monthly subscriptions and a reduced rate for a yearly subscription."*

The prompt begins with useful context about the relevant email. Next, it clearly states that the task is to summarize the main points of the email. Finally, it specifies that the output should be formatted as a bulleted list.

**Note:** Be aware that LLMs can sometimes hallucinate, or produce AI outputs that aren’t true. In this case, the LLM might add details to the summary that aren’t included in the source email. Always evaluate LLM output for accuracy before using it.

### **Classification**

Text classification is another common workplace application for LLMs. An LLM can help you sort customer service emails into categories based on the content of the email, categorize content in social media posts, and analyze the sentiment or feeling of customer feedback. The following prompt asks an LLM to analyze the sentiment in a customer review:

*Read these customer reviews and tell me whether the sentiment of the reviews is positive, negative, or neutral.*

*Customer Review: I don't know where to begin. We had reservations for 7:00 but they seated us at 7:45. Then, no one came to our table for at least 30 minutes. Our appetizer and main course were mediocre. I did love the dessert, but that wasn't enough to change our experience.*

*Customer Review: I love this restaurant. The food is delicious and the service is excellent.*

The prompt begins by clearly stating that the task is to analyze the sentiment of a customer review and then specifies the options: positive, negative, or neutral. Then, the prompt includes the relevant reviews under the label “Customer Review.”

### **Extraction**

You can also use an LLM to pull data from text and transform it into a structured format that’s easier to understand, known as extraction. For example, this prompt asks an LLM to review a blog post and extract information about products mentioned in the post.

*Read the blog post below and extract all of the references to items of clothing I can buy and how much each item costs. Create a bulleted list of just these items.*

*Blog post: Hey everybody, I want to share what I’m wearing on campus this fall. If I’m going out for the evening, I prefer the raw selvedge denim jeans ($150) paired with the cashmere crew neck sweater ($250). For a more casual look, I like the fleece hoodie ($99) and fleece sweatpants ($129). I also love every color of the striped socks ($15). They pair well with both the jeans and the sweats.*

The prompt begins by clearly stating that the task is to extract all the items of clothing mentioned in the blog with their corresponding prices. Next, the prompt specifies that the format of the output should be a bulleted list of the items. Finally, the prompt includes the relevant blog.

### **Translation**

You can leverage an LLM to translate text between different languages very quickly. For example, the following prompt asks an LLM to help translate product descriptions from English to Spanish:

*Translate our product descriptions from English to Spanish. Maintain the same structure and casual tone that is used in the English version in the Spanish translation.*

*Bicycle: Whether you’re exploring city streets or forest paths, our sleek and durable bicycle has it all.*

*Rollerblades: Roll into summer in style with our smooth and stylish rollerblades.*

The prompt begins by clearly stating that the task is to translate product descriptions from English to Spanish. It also specifies that the Spanish translations should maintain a similar structure and tone as the English originals. Finally, each example contains a label that introduces the product description: “Bicycle" and “Rollerblades.” This format indicates that the LLM should present the output in a similar form.

**Note:** As a best practice, confirm that an LLM’s translations are accurate by cross-checking with another translation tool.

### **Editing**

You can also use an LLM to edit and rewrite text. The LLM can help change the tone of the text from formal to casual, or complete a grammar check. For example, the following prompt asks an LLM to help edit a technical report so that it’s less jargony and easier for stakeholders to understand:

*Edit the language of the following paragraph so that it's easy for a general audience to understand it. Use simpler vocabulary and grammatical structures but maintain the same ideas.*

*Site selection for expansion is a complex and multifaceted process. The west side site offers several advantages, including zoning for industrial use and direct access to both a major highway and railroad. However, the site is also located in a jurisdiction with a complex and time-consuming permitting process, and its distance from residential zones may necessitate higher wages to attract workers.*

The prompt begins by clearly stating that the task is to edit the text to make it easier for a general audience to understand. Then the prompt specifies that the text’s vocabulary and grammar should be simplified while its main content should remain the same. Finally, it includes the relevant paragraph.

### **Problem-solving**

One more use case is problem-solving. You can use an LLM to generate solutions for a variety of workplace challenges, from analyzing sales data to planning an event. For example, the following prompt asks an LLM to help organize a program for a nonprofit organization:

*We are running a community program to teach children gardening skills. The program runs from June 1 to August 15. We want the children to be able to grow plants that will be ready for harvest by the time the program ends. First, identify a list of 10 plants that can be planted and grown in that time period. Include sources that support the time to harvest for each plant.*

*We want the children to grow three plants. These plants should be as different from each other as possible. So next, choose three plants from the list that will provide the children with this variety.*

The prompt begins with useful context about the program, such as its main purpose and timeline. Next, the prompt breaks the problem down into two main steps: First, identify a list of 10 plants that fit the timeline, and second, choose three plants from the list that are unlike each other. The prompt also asks the LLM to include sources for the list of 10 plants. Asking the LLM to cite its sources in the output helps you verify the accuracy of the information used to solve the problem.

![Untitled](Module%203%20cf3d06aec1fd40e98e7b2d74f63fb4b5/Untitled.png)

[Improve AI output through iteration](https://www.coursera.org/learn/google-ai-essentials/lecture/MW1gy/improve-ai-output-through-iteration?trk_ref=coach_copy)  Jun 5, 2024

## Summary of the video:

This video discusses the importance of taking an iterative approach to prompt engineering. It highlights that getting the optimal output from a large language model (LLM) often requires multiple attempts and revisions.

Here are the key takeaways:

- **Iterative process:** Just like creating a presentation or website, prompt engineering involves an iterative process of refining your prompts to achieve the desired outcome.
- **LLM differences:** Different LLMs have different strengths and weaknesses, so you may need to adjust your prompts depending on the specific model you're using.
- **LLM limitations:** LLMs can sometimes produce inaccurate, biased, insufficient, irrelevant, or inconsistent output. It's important to critically evaluate the output and iterate on your prompts to address these issues.
- **Prompting tips:** Consider adding context, using different words or phrasing, and specifying the desired format of the output to improve your results.
- **Example:** The video provides an example of how to iteratively refine a prompt to create a list of colleges with animation programs in Pennsylvania, organized in a table format.

By following these tips and taking an iterative approach, you can effectively leverage LLMs to achieve your desired outcomes.