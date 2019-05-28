# Exploring development communication scholarship through the years: The Los Baños School of Development Communication 70 years hence

Rikki Lee B. Mendiola
Eskwelabs Fellow, Data Science Manila Cohort 1

Manyozo (2006) written a manifesto that placed Nora C. Quebral at the beginning of development communication scholarship—coining it in the 1950s in her seminal lecture while still under the UP Los Baños College of Agriculture. It was a different lens on looking at the scholarship away from the western development communication scholarship that began with Everette Rogers (diffusion of innovation). The Los Baños school has been recognized in pioneering “reflexive, method-driven and theory-based nature of development communication experiments were participatory and conceived as rural development interventions in themselves, concepts that formulate foundation stones of modern-day global discourse in development communication.”
					
While it has been years since Quebral coined the concept of development communication, the growth of the discipline has not been traced completely. While there are attempts to look at the scholarship, the meta analysis was limited to a small sample of studies across different origins (Manyozo, 2006; Waisbord, 2001; CDC, 2001). For the capstone project, I want to study the typologies of development communication research produced under instruction (dissertations, masters and undergraduate theses) as a manifestation of the scholarship throughout the years. This will start a reflexive exercise on looking at where the discipline has progressed, and on the directions the college can pursue.

For this capstone project, I want to work on the database I have been building for the past year. From the digitization project of my College, a team of students helped me parse the text from images. The data starts from 1979 to 2018. I intend to apply data science in knowledge management—while strategy and information technology are two key areas of KM, data science can transform data to knowledge that can start action and creation of vision.

Questions I want to answer
In general, I want to map the progress of the Los Baños School in the development communication scholarship. Here are the initial questions I want to answer:

- What are the research themes?
- What are the quantitative and qualitative methodologies used in research studies?
- Where are the research sites of these studies?
- What are the communication traditions emerging from the studies?

For my stretch goals, I want to look at how I can develop a ML solution for classifying methodology and communication strategy of a study.

The table includes these fields (some of the insights I need, I still need to extract from the existing fields):

THESES TABLE FIELDS ` (
`thesisid` INT(10) NOT NULL, 
`user_id`INT(10) NOT NULL, 
`date_approved` DATE, 
`date_submitted` DATE, 
`title` TEXT, 
`abstract` TEXT, 
`keywords` TEXT, 
`pdf` VARCHAR(30), 
`level` VARCHAR(16), 
`createdAt` DATE, 
`updatedAt` DATE
);

However, I still need to think about how I can narrow the scope, depending on the time I can work on the capstone project.
