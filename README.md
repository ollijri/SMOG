# The SME OSINT Guide for Due Diligence (SMOG)

### Introductory Information 🌟

<details>

<summary><b>Why Was This Made?</b></summary>

  <br>
  
  This guide was made as part of my dissertation submission.
  
It has been found that while employers understand that background checks must be conducted, they do not know how to conduct them themselves. Literature has also found that reports often talk about the need for checks but do not discuss how to do so. 
  
This proposed methodology aims to have a user-friendly design and aims to be understandable to individuals at any level of technical ability.
  
By focusing on user comprehension, the methodology attempts to close the gap between the employers understanding of the need to conduct checks, and their ability to do so.
 
  <br>
  
</details>

<details>

<summary><b>Who Is This For?</b></summary>

  <br>
  
The primary audience for this is UK-based SMEs to help conduct their due dilligence in the background checking stage of hiring. This guide can be used by anyone. The examples provided and wording is, however, tailored towards hiring practices. 

</details>

<br>



📋 <i> The user of this methodology must employ fair hiring practices and must not use this guide to discriminate against individuals or groups based on perceived characteristics.  </i>

📋 <i> The individual "William Jenkins" referenced throughout this guide serves purely as an example and does not represent a real person. </i>
____________________________________________________________________________________________________________________

### Google Dorking 🌍

- [ ] Simple Google Search of Target's Name
- [ ] Google Dork Search of Name + Location
- [ ] Google Dork Search of Name + Local News
- [ ] Google Dork Search of Name + Key Interest of Applicant (If Known)

<details>

  <summary><b>What is Google Dorking?</b></summary>

  <br>

  Google Dorking (also known as Google Hacking) is the act of using advanced 'search operators' in the search bar of Google to obtain information that would be otherwise hard to find by refining your search results. 
  
  <br>
  
  By correctly utilising Google Dorking, you can uncover the following information that relates to this stage in the investigation:
  
  - Usernames <--- This is what we want to be looking for as a top priority
  - Personally Identifiable Information
  - Email Addresses
  
  <br>
  
</details>

<details>

<summary><b>What 'Search Operators' Can I Use To Assist in Google Dorking?</b></summary>
  
  <br>
  
| Operator | Usage | Example |
| --- | --- | --- |
| "" | Specifies words MUST be in search results | "William Jenkins" |
| - | Excludes words from search results | "William Jenkins" -Census |
| site: | Restricts results to a specific site | "William Jenkins" site:facebook.com |
| OR | Searches for multiple words as alternatives to one another | William OR Will |
| AND | Restricts results to those that include both words | "William Jenkins" AND "Cyber Security" |
| allintext: | Only shows results where the text is in | allintext:William Jenkins |

</details>

____________________________________________________________________________________________________________________

### Username OSINT 💻

- [ ] Simple Google Search of Username
- [ ] Locate Additional Social Media Not Found Through Google Dorking
- [ ] Locate Other Sites of Legitimate Interest Using Target Username

<details>

<summary><b>Where Could We Look for Potential Usernames?</b></summary>

<br>
  
The easiest and most obvious places to look are within the profile page of any identified social media pages from the results of Google Dorking. Once one username has been identified, this can be run through a 'Username Checking Site' to try to locate further accounts linked to the target.
  
| Site | Location | Example |
| --- | --- | --- |
| Facebook | Within the URL on the target's profile | facebook.com/Jenkins123/ |
| Twitter | Underneath the account name on the profile | @Jenkins123 |
| Linkedin | Within the URL on the target's profile | linkedin.com/in/Jenkins123/ |
| Tiktok | Within the URL on the target's profile | tiktok.com/@Jenkins123 |

<br>
  
</details>

<details>

<summary><b>What Can We Do With These Usernames?</b></summary>

  <br>
  
  The located usernames can be put into a 'Username Search Site' (See Table) which will crawl the internet for accounts with identical usernames and provide links to them for you in a clean and presentable format.
  
  | Site | Why? |
  | --- | --- |
  | [Whats My Name](https://whatsmyname.app/) | Tracks accounts based off username and categorises them by site type and provides a link to each |  
  | [Instant Username Search](https://instantusername.com/) | Well formatted and responsive site that updates as you type and displays found sites linked to that username in a tidy format |

  <br>
  
</details>

<details>

<summary><b>How Do I Use Username Search Sites?</b></summary>

  <br>
  
<details>
  
<summary><b>Whats My Name</b></summary>

<br>
  
On loading the website you will be greeted with the search bar seen below:
  
![image](https://github.com/ollijri/SMOG/assets/66912443/735ad882-2b5a-429a-aa49-dc38ded32723)
  
The blue button on the left allows you to tailor your search to accounts based off of a certain category. This includes but is not limited to dating, coding and shopping sites.
  
To begin searching, enter the username into the white box and press the green button. If you wish to add multiple usernames, add a new line and enter the next username below the first like so:
  
![image](https://github.com/ollijri/SMOG/assets/66912443/40ede48f-827f-475d-adf1-f1b5e7abced7)
  
This will produce a list of all the accounts which share a username with the ones you have entered. The information on the left and the right is the same, they are just formatted differently so use either depending on your preference.
  
  <br>
  
 <p align="center">
 <img src=https://github.com/ollijri/SMOG/assets/66912443/31246b8e-9c54-4497-9117-78b6f2e59174>
 <br>
   <i> The output on the left </i>
 <br>
   <br>
 <img src=https://github.com/ollijri/SMOG/assets/66912443/ba93ddd4-03e5-48b7-8b9c-ead728a1b5ca>
<br>
  <i> The output on the right </i>
   <br>
    <br>
 </p>
  
 <br>
  
</details>

<details>

<summary><b>Instant Username Search</b></summary>

  <br>
  
  On loading the website you will be greeted with the search bar seen below:
  
  ![image](https://github.com/ollijri/SMOG/assets/66912443/f82c9858-530d-451d-9c75-9d7e48784600)
  
  To begin searching, enter the username into the white box and the website will automatically populate with accounts. If you wish to use multiple usernames at once, 'Whats My Name' is a better site for you.
  
  As seen below, the accounts which have identical usernames will be crossed out, these can be clicked on to redirect the user to the site referenced on the box and to the account profile of the connected username
  
  ![image](https://github.com/ollijri/SMOG/assets/66912443/e84af528-e26d-4698-8894-c636110cc480)
  
  
</details>
  
</details>

____________________________________________________________________________________________________________________

### Social Media OSINT 💻

By this stage, hopefully the 'Username OSINT' and 'Google Dorking' techniques will have led you to find at least one social media account linked to the target. 


The next step is to consider the content of the accounts to see if the target will be detrimental to your business:

- [ ] Search Facebook Profile
- [ ] Search Twitter Profile
- [ ] Search LinkedIn Profile
- [ ] Search Other Sites of Interest Located in the 'Username OSINT' Section

<details>

<summary><b>What If The Account Is Private?</b></summary>
<br>
If the account is private, thats it. Its private. Do not believe the sources you see online that claim you can "sign up now to see all contents of a private account", they are scams.

</details>

<br>

📋 <i> In accordance with Article 8 of the European Convention of Human Rights, the user of this guide must be mindful of the content they are viewing during their investigation and must make an effort to maintain a balance between information gathering and respecting a target's privacy rights. </i>

____________________________________________________________________________________________________________________

### Obtaining Criminal Records of Target 👮

Criminal record checks in the UK are only available through the Disclosure and Barring Service (DBS) and the user will have to rely on requesting it from the target.

- [ ] Request DBS Certificate

📋 <i> In accordance with the Police Act (1997), if it is necessary to have a copy of the information from the DBS Certificate, the user must make sure the data is destroyed after a suitable period which is typically no more than 6 months. For more information, click [here](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/474742/Code_of_Practice_for_Disclosure_and_Barring_Service_Nov_15.pdf) </i>


📋 <i> In accordance with the Rehabilitation of Offenders Act (1974), employers cannot turn away an applicant due to a spent conviction and must treat the applicant as though the conviction had not happened. For more information, click [here](https://www.gov.uk/government/publications/dbs-sample-policy-on-the-recruitment-of-ex-offenders/sample-policy-on-the-recruitment-of-ex-offenders) </i>
____________________________________________________________________________________________________________________

### Current/Previous Company Search 🏢

If the target states they have worked for companies before that spark your interest (especiall if they are big names), it is important to verify this information. 

If they claim to have owned their own company before, this information can also be verified using the Company Register on the GOV.UK website.

- [ ] Check GOV.UK Company Register
- [ ] Check LinkedIn

<summary><b>How Can I Conduct an Effective Search On the Company Register?</b></summary>

</details>

<details>

<summary><b>How Can I Conduct an Effective Search On LinkedIn?</b></summary>

</details>

____________________________________________________________________________________________________________________

### Obtaining Qualification Information 🏫

It is suggested for the user to request to see the official certificate for their qualification upon interview in order to get an idea on whether the applicant is truthful.

Unfortunately, in the UK, the target's qualification information can only be verified by contacting the awarding institution.


- [ ] Request Official Certificates From Applicant

____________________________________________________________________________________________________________________

### Obtaining Vehicle Information of Target 🚗

The best and most reliable way to obtain vehicle information in the UK is through the [Driver and Vehicle Licensing Agency](https://www.gov.uk/government/organisations/driver-and-vehicle-licensing-agency) (DVLA). 

This section assumes that the user knows the number plate of the target vehicle.

- [ ] Check Driving License Information
- [ ] Conduct Vehicle Enquiry

<details>

  <summary><b>How Do I Check Driver's License Information?</b></summary>
<br>
  
  The section of the DVLA website which the user will need to visit is the [Check Driving Information](https://www.gov.uk/check-driving-information) page. This allows the employer to find out whether the applicant has any penalty points or disqualifications:
  
  ![image](https://github.com/ollijri/SMOG/assets/66912443/e8703db7-beaa-4461-986c-0bc8fe419886)

  <br>
  
 📋 <i>A check code is also required which means getting consent from the applicant to share this information. The applicant will need to go [here](https://www.gov.uk/view-driving-licence) to get their sort code</i>
  
</details>

<details>

  <summary><b>How Do I Effectively Conduct a Vehicle Enquiry?</b></summary>
  <br>
  
  The section of the DVLA website which the user will need to visit is the [Vehicle Enquiry Service](https://vehicleenquiry.service.gov.uk/)
  
  This allows employers to check whether an applicant's vehicle is taxed, the MOT information, engine size, weight etc:
  
  ![image](https://github.com/ollijri/SMOG/assets/66912443/dd64af45-e9d4-4e47-b618-47a383c7fd33)
  
</details>
