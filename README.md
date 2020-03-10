## Bonobot 

Bonobot is a web-based chatbot agent that delivers a brief motivational interview for graduate students.

### Motivation
Recent technological adaptations of psychotherapy, including chatbots, avatars and embodied agents, often lack design transparency especially in terms of theoretical background. Behavior-based techniques are popular in technological implementation as they do not require a sophisticaed natural language understanding on the machine's part. However, parroting a series of exercises and routines may risk not only adherence and engagement but also effect and safety. We built Bonobot, a mental health chatbot that closely follows the practice and guidance of motivational interviewing.   

### Motivational Interviewing
Motivational interviewing (MI) is a directive, client-centered counseling appraoch to elicit positive behavior change from clients by helping to explore and resolve their ambivalence. Originally used to treat addiction and substance use problems, MI has increasingly been introduced in mental health domain, for instance as a [pretreatment](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2760690/) for cognitive behavior therapy. MI has specific counselor behaviors/techinques, or "micro-skills" as we call it, which can be coded and quantitatively measured to tally MI-adherent/nonadherent behavior leading to client change talk.  

### Design
Using the MI micro-skills, we designed a four-staged MI session in a chatbot conversation. In each stage, we allotted specific sequences of MI micro-skills for chatbot responses. To maintain conversation context, we listed up 100 topical keywords extracted from analyzing Reddit posts ([r/PhD](reddit.com/r/PhD) and [r/GradSchool](reddit.com/r/GradSchool)). Each keyword entails sequences of MI micro-skills, one of which is used for a designated turn in a given stage of conversation. Examples of Bonobot conversation can be found below. For more information, please refer to our [research article](https://www.jmir.org/2019/4/e12231/). <br>
<img src="/example/engaging.png" width="550px" height="500px" alt="Engaging"></img><br/>
<img src="/example/focusing.png" width="550px" height="500px" alt="Focusing"></img><br/>
<img src="/example/evoking.png" width="550px" height="500px" alt="Evoking"></img><br/>

### Acknowledgement
For source, contact [one](https://github.com/cockroach54/Bonobot) of our awesome research collaborators! 


