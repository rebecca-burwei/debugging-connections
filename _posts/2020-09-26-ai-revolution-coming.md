---
layout: post
title: "The AI Revolution is coming, and I’m automating away the jobs."
date: 2020-09-26
truncatewords: 23
background: '/img/posts/20200926.jpg'
---

Over 75 million jobs from retail to finance to transportation and healthcare will be eliminated by AI, according to McKinsey predictions for 2030.[^1] 

Drivers, office assistants, retail and food service workers will be the most affected by automation. 

However, many professionals like early-career lawyers or doctors will also be affected by automated enhancements to their work.

---
> As a data scientist, I have automated both routine and skilled work with machine learning. 

---

Sometimes, these tasks are as mundane as identifying whether or not a picture contains a car. Other times, they are highly specialized like organizing legal paperwork. 

In the tech industry, it's easy to fall into zero-sum thinking: We get to build these cool machine-learning models, only if other people lose their jobs. How do we break out of this binary way of thinking? And more importantly, **how could we support those whose jobs we're automating?**

To answer these questions, we need to figure out how our automation work fits in to larger labor trends. To do this, I offer examples from the history of automation as well as two of my own work experiences as case studies. Then, I give ways to change our thinking and look towards solidarity. 

# History of automation

## Which jobs are we automating? Which jobs are we creating?

Let’s start with an example from history as a guide.

From the 1850s to 1880s, advances in steam power and electricity led to a wave of automation in US manufacturing. Middle-skilled artisans were replaced with a combination of low-skilled machine operators and high-skilled engineers to install and maintain the machines. The number of middle-skill artisan jobs declined while the number of both high-skill and low-skill jobs increased. Within manufacturing, this resulted in a hollowing out of middle-skill jobs.[^2]

## Is automation hollowing out middle-skill jobs today?

Yes, from trucking to medical imaging to supply-chain planning, in many ways, it is. 

At Allstate, an auto insurance company, I worked on a project to automate the decision-making process for claims adjusters. In insurance, adjusters use specialized knowledge to make many decisions, including who is at fault in a car accident, what repairs are needed, and how much the repairs should cost.

While it takes time to develop the specialized knowledge needed to be an adjuster, there is also a high amount of turnover in the position. From the company's perspective, it takes a long time for adjusters to learn their skills, and then they leave. The company doesn't get to reap the full benefits of having skilled adjusters, making adjusters a prime target for automation. 

As data scientists, we interacted infrequently with adjusters. But occasionally, we could employ adjusters to create the data we needed to build our models. Our models needed hundreds of thousands of annotated photos. Adjusters spent weeks annotating photos by answering questions about them. The types of questions ranged from simple (Is this a photo of a car?) to specialized (How serious is the damage on this vehicle?). However, there were always many more simple than specialized questions to answer. In the end, all this data was put into a machine-learning model to automate decision-making for adjusters who assessed [total losses](https://en.wikipedia.org/wiki/Total_loss).

When we raised concerns about automating our colleagues’ jobs, the company responded that no lay-offs would be needed because the high turnover rate meant that adjusters would organically leave their positions. When these adjusters “organically” left their jobs, they left middle-skill specialized work, and were familiar with low-skill, data annotation gigs---thanks to having annotated data for our models. 

At scale, I believe this type of data annotation engagement facilitates the hollowing out of middle-skill work. We facilitated down-skilling and reduced opportunities. We greased the wheels of the AI Revolution transforming specialist work into low-skill gigs. 

## Do we have to be the facilitators of downskilling?

Businesses often argue that automation allows workers at all skill levels to focus on higher-value tasks, such as customer interactions or higher-level planning. However, up-skilling doesn’t happen without intention. Let’s look back at history.

In the 1940s and 50s, as auto manufacturing became more mechanized, Japanese managers up-skilled their assembly-line workers by adding collaborative quality control to their responsibilities. Workers no longer just performed the same task over and over, but were also responsible for evaluating and ensuring product quality. In quality circles, they worked together to identify and resolve issues in the manufacturing process. 

On the contrary, in the same era of mechanization, American managers chose to down-skill their workers. By continuing to follow Fordian principles, American managers assigned workers to ever smaller and more repetitive, routine, low-skill tasks.[^3]

## How might we resist facilitating down-skilling?
 
One of my first clients was the International Center for Advocates Against Discrimination (ICAAD). As an advocacy non-profit, ICAAD wanted to classify reports of human-rights violations according to the UN’s focus areas. In machine learning jargon, ICAAD wanted to solve a multi-class text classification problem. There were 17 classes, and many of the documents involved heavy legalese.[^4]

After trying some creative ideas with synthetic and implicitly annotated data, our team concluded that tens of thousands of documents would still need to be manually annotated. While we could do the annotation ourselves, it was very time-consuming because we data scientists were unfamiliar with the legal terms. Instead, we partnered with volunteers from ICAAD’s legal team to do the annotation. 

In this exchange, ICAAD annotators created a glossary of legal terms, human rights actions and anti-discrimination policies that they could share with their entire organization. While the glossary was originally created to increase the consistency and quality of data annotation, it turned out to be a useful, re-usable resource for educating their volunteers.

Yes, we built a model for ICAAD to automate the dull task of classifying documents. However, in the exchange, ICAAD also built for themselves an educational glossary, which would help current and future volunteers learn the lay-of-the-land in international human rights. This created opportunities for more lay people to educate themselves on international human rights and become informed advocates. 

## We didn't just do machine learning.

---
> We extracted knowledge from volunteers and commodified it in two ways: as a machine learning model, and as an educational resource for future volunteers. 

---

From these two case studies, we see how machine-learning automation can eliminate opportunities and facilitate downskilling via the huge demand for data annotation. However, with intention, we can also use data annotation as an opportunity to build resources to benefit the people we’re extracting knowledge from.

Based on these case studies, I close with ways to transform our perspective and look towards solidarity.

## Data annotation as knowledge exchange, not knowledge extraction.

As data scientists, we are in the business of knowledge extraction and commodification. We take knowledge from people and commodify it in the form of a model. 

However, we could reframe the business of knowledge extraction instead as knowledge exchange. Exchange takes many forms, and need not be uniform across all data annotation engagements. Exchange could look like collaborating on a re-usable knowledge base, exchanging insights to reduce model biases, or transforming the temp job of data annotator into an on-ramp for a stable job in model maintenance. It could look like [something else](https://sloanreview.mit.edu/article/will-ai-create-as-many-jobs-as-it-eliminates/) entirely. Let’s get creative and reframe data annotation as more than just knowledge extraction.

## We participate in global supply chains of data extraction, transformation and augmentation.

Data annotation is now a global multi-million dollar business. The market is no longer dominated by platforms like Amazon’s Mechanical Turk paying gig workers a pittance to classify pictures of cats and hot dogs (although the exploitatively low pay of contract annotators is still a major problem!). 

Instead, many applications like autonomous driving and medical imaging require specialized, high-quality annotation in huge amounts. Entrepreneurs around the world are forming full-service companies to manage all of your data annotation needs, and train both full-time and contract workers to annotate for technical tasks.[^5]

As downstream users of data, we are connected to Indian women performing highly technical annotation, Kenyans and Ugandans using annotation as a stepping stone for getting into tech, US veterans annotating sensitive data that must remain in the US, and many more. We are connected via global supply chains of extraction, transformation and augmentation of data. 

How can we use these supply-chain connections to make our exchanges and trades more equitable?

The landscape of data annotation services is diverse and changing. Here are a few starting points to learn more about it:
- <ins>[These companies claim to provide "fair trade" data work. Do they?](https://www.technologyreview.com/2019/08/07/133845/cloudfactory-ddd-samasource-imerit-impact-sourcing-companies-for-data-annotation/)</ins> (ignore the click-baity title)
- <ins>[The AI sharecroppers](https://www.axios.com/the-ai-sharecroppers-b316d333-ce00-47a1-afd5-219d6138461e.html)</ins>
- <ins>[How India’s data labellers are powering the global AI race](https://factordaily.com/indian-data-labellers-powering-the-global-ai-race/)</ins>

## We play a strategic role in the economics of AI, but not the only role.

The reason why retail jobs will be cut in the US and data annotation jobs created globally is the same--it’s cheaper for big businesses. As data scientists, we play a crucial role on both sides of this enterprise: we supply models that enable automation, and we create demand for data annotation work. Our labor is valued and well-regarded because it disrupts how others will work. Thus, as work disrupters, we have a responsibility to make the process and outcomes of the AI Revolution economically just.

But we can’t do this alone. And neither should we lead all of the efforts. Progress, in many forms, is driven by people whose labor is undervalued. For example, many advances in agricultural automation, like the mechnical cotton harvester, were driven by a shortage of labor when farm workers refused exploitative work. When formerly enslaved sharecroppers and im/migrant farm workers refused exploitation, then US farm owners finally invested in innovation and machine-building.[^6] 

---
> We are affected by the actions of the workers whose jobs we’re automating, just as they are affected by ours. 

---

# Final Takeaways

Facing the inevitability of automation, I encourage data scientists not to passively accept our roles as harbingers of automation. Let's get excited about supporting our co-workers just as we are about the latest in deep learning. We have opportunities in the model-building process to connect with and support the people whose jobs we’re automating as well as with those who annotate data for us.

The rat race of model-building trains *us* to extract, devalue and commodify our co-workers’ as well as our own knowledge. By shifting our goals from knowledge extraction to knowledge exchange, we *unlearn* the devaluation others’ labor and take a first step towards solidarity.

# Footnotes

[^1]: McKinsey Global Institute (2017). Jobs Lost, Jobs Gained: Workforce Transitions In A Time Of Automation. Retrieved 2020-09-11 from <ins>[here](https://www.mckinsey.com/~/media/mckinsey/industries/public%20and%20social%20sector/our%20insights/what%20the%20future%20of%20work%20will%20mean%20for%20jobs%20skills%20and%20wages/mgi%20jobs%20lost-jobs%20gained_report_december%202017.pdf)</ins>.

[^2]: Katz, Lawrence F. and Margo, Robert A. (2014). Technical Change and the Relative Demand for Skilled Labor: The United States in Historical Perspective. Retrieved 2020-09-11 from <ins>[here](https://scholar.harvard.edu/lkatz/publications/technical-change-and-relative-demand-skilled-labor-united-states-historical-persp)</ins>.

[^3]: Kranzberg, Melvin and Hannan, Michael T. (2017). Encyclopædia Britannica, History of the organization of work. Retrieved 2020-09-11 from <ins>[here](https://www.britannica.com/topic/history-of-work-organization-648000/Automation#ref67058)</ins>.

[^4]: “One of my first clients” -- <ins>[DataKind](https://www.datakind.org/)</ins> connected me to this client, and I worked with two fantastic data scientists: <ins>[Karry Lu](https://www.linkedin.com/in/karry-lu-a97ab122)</ins> and <ins>[Ben Cohen](https://www.linkedin.com/in/bthecohen/)</ins>.

    “UN focus areas” = UN’s Sustainable Development Goals.

[^5]: “global multi-million dollar business” -- Cognilytica (2019). Data Engineering, Preparation, and Labeling for AI 2019. Retrieved 2020-09-11 from <ins>[here](https://www.cognilytica.com/2019/03/06/report-data-engineering-preparation-and-labeling-for-ai-2019/)</ins>.
    
    “exploitatively low pay of contract annotators" -- Gray, Mary L. and Suri, Siddharth. Ghost Work: : How to Stop Silicon Valley from Building a New Global Underclass. Houghton Mifflin Harcourt, 2019.

[^6]: Taber, Sarah (2019). Tweet. Retrieved 2020-09-11 from <ins>[here](https://twitter.com/SarahTaber_bww/status/1116687787078619137)</ins>.