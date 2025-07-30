# Edtech-Lead-Conversion-Prediction overview
Over the past decade, the EdTech industry has exploded worldwide. In fact, the global online education market is projected to reach $286.62 billion by 2023, growing at a compound annual growth rate (CAGR) of 10.26 percent from 2018 to 2023. Driven by features like seamless information sharing, personalized learning paths, and transparent assessments, platforms such as ExtraaLearn, Coursera, and Udemy are rapidly eclipsing traditional classroom models.

The COVID‑19 pandemic only accelerated this shift. As more learners turned online, a wave of new EdTech startups and established players alike raced to capture attention. With digital marketing tools at their fingertips, these companies generate thousands of “leads” every day—that is, prospective students who show initial interest. Leads typically arise when:

A visitor engages with an ad or post on social media

A prospect browses the website or mobile app and downloads a program brochure

An individual emails or chats to request more information

From there, sales and support teams at ExtraaLearn, Coursera, and others nurture each lead—via follow‑up calls, personalized emails, and targeted content—with the goal of converting them into paying customers.

# Objectives adressed

1. Analyzing and build an ML model to help identify which leads are more likely to convert to paid customers.

2. Finding the factors driving the lead conversion process.

3. Creating a profile of the leads which are likely to convert.

# Data Description
The data contains the different attributes of leads and their interaction details with ExtraaLearn. The detailed data dictionary is given below.

- ID:ID of the lead

- age:Age of the lead

- current_occupation:Current occupation of the lead. Values include 'Professional', 'Unemployed', and 'Student'

- first_interaction:How did the lead first interact with ExtraaLearn? Values include 'Website' and 'Mobile App'

- profile_completed:What percentage of the profile has been filled by the lead on the website/mobile app? Values include Low - (0-50%), Medium - (50-75%), High (75-100%)

- website_visits:The number of times a lead has visited the website

- time_spent_on_website:Total time (seconds) spent on the website.

- page_views_per_visit:Average number of pages on the website viewed during the visits

- last_activity:Last interaction between the lead and ExtraaLearn

- Email Activity:Seeking details about the program through email, Representative shared information with a lead like a brochure of the program, etc.
- Phone Activity:Had a phone conversation with a representative, had a conversation over SMS with a representative, etc.
- Website Activity:Interacted on live chat with a representative, updated profile on the website, etc.
- print_media_type1:Flag indicating whether the lead had seen the ad of ExtraaLearn in the Newspaper

- print_media_type2:Flag indicating whether the lead had seen the ad of ExtraaLearn in the Magazine

- digital_media:Flag indicating whether the lead had seen the ad of ExtraaLearn on the digital platforms

- educational_channels:Flag indicating whether the lead had heard about ExtraaLearn in the education channels like online forums, discussion threads, educational websites, etc.

- referral:Flag indicating whether the lead had heard about ExtraaLearn through reference.

- status:Flag indicating whether the lead was converted to a paid customer or not. The class 1 represents the paid customer and class 0 represents the unpaid customer.

# Data Driven Insights

1.Leads exhibiting elevated engagement—measured by time spent on the website (>422.5 seconds), multiple visits, and higher page views per session—demonstrate a significantly greater likelihood of conversion. These users should be prioritized in marketing and sales outreach.

2.Leads acquired through referral channels consistently show higher conversion rates compared to non-referred users. Strengthening referral programs could enhance overall lead quality and improve acquisition efficiency.

3.Leads aged 27.5 years or younger, particularly those with active engagement and from professional or student segments (excluding unemployed), exhibit higher conversion probabilities. Tailored messaging and targeting strategies should consider these demographic traits.

4.Leads whose first interaction occurred via the website, followed by consistent activity, are more likely to convert. Improving the user onboarding flow, engagement hooks, and content on the website could further boost lead quality.

5.Leads with low profile completion are strongly correlated with non-conversion. Implementing personalized nudges or progressive profiling techniques may encourage users to complete their profiles and increase conversion likelihood.

6. Exposure to digital and print media, when paired with subsequent website interaction, correlates positively with conversion outcomes. A multi-touchpoint marketing approach can be effective in driving intent and reinforcing brand presence.
