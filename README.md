<img width="1280" height="640" alt="git (1)" src="https://github.com/user-attachments/assets/8920b256-2ba8-4988-b824-5351134eb4bd" />



VAMSHA VISHAKALANAM


## Basic Details
### Team Name: Kakka.exe


### Team Members
- Team Lead: RESHMA.R - SCMS SCHOOL OF ENGINEERING AND TECHNOLOGY
- Member 2: VANDANA SUDEEP - SCMS SCHOOL OF ENGINEERING AND TECHNOLOGY


### Project Description
Vamsha Vishakalanam is a crow detection website that treats every crow photo like a government case file — confirming ancestry, assigning a name, age, place, and cause of death, all with the seriousness of a real bureaucracy and the accuracy of a coin toss.

### The Problem (that doesn't exist)
Every day, countless crows are spotted perched on walls, wires, and windowsills — yet no one asks the obvious question: whose ancestor is this? Despite a centuries-old belief that crows carry the spirits of the departed, there is currently no digital infrastructure to verify a crow's identity, confirm its previous life, or determine how it died. Families are left to simply assume the crow outside their window is a relative, with no official record, no certificate, and no accountability. Vamsha Vishakalanam solves this glaring gap in ancestral record-keeping by providing instant, deeply unqualified identification of any crow submitted for review.

### The Solution (that nobody asked for)
Vamsha Vishakalanam is a website that closes this gap by turning crow identification into a formal (looking) process. Users upload a photograph, which is reviewed through an image-analysis pipeline to first confirm the subject is, in fact, a crow — rejecting pigeons, cats, dogs, and other imposters with appropriate offense. Once confirmed, the crow is issued an official ancestral record: a name, age at death, place of origin, and cause of death, generated consistently so the same crow always receives the same identity on repeat visits. A shared sightings ledger even tracks how often each identified crow has been spotted by the community that week — turning casual crow-watching into verifiable (if entirely fictional) ancestral record-keeping.

## Technical Details
### Technologies/Components Used
For Software:
- HTML, CSS, JavaScript, TensorFlow.js, Chart.js
- NILL
- TensorFlow.js, Chart.js
- VSCode, Browser DevTools, TensorFlow.js Layers, Claude, Chart.js

### Implementation
For Software:
# Installation
No installation required.

# Run
Double-click vamsha-vishakalanam.html and it opens directly in your default browser

### Project Documentation
For Software:

# Screenshots (Add at least 3)

<img width="976" height="781" alt="Title Screen" src="https://github.com/user-attachments/assets/93bbf275-64a5-4a0e-a4ba-465ff373549c" />


This is the landing screen of the Vamsha Vishakalanam website — the first page a visitor sees. It opens with a small kicker line reading "office of ancestral records · unofficial branch," which immediately establishes the site's mock-bureaucratic tone by framing it as a fictional government office. Below that sits a circular stamp emblem containing a stylized crow silhouette, reinforcing the "official document" aesthetic that runs throughout the site. The page then displays the project's name, "Vamsha Vishakalanam," in large serif type, followed by the tagline "a modest inquiry into feathered inheritance," which hints at the site's core premise — crows as carriers of ancestral inheritance — while keeping the tone formal and deadpan. A final supporting line, "Case files opened, ancestry cross-examined, dignity optional," adds a touch of humor before the user commits to continuing. The page ends with a "Begin the enquiry" button, which takes the user forward to the about screen, where the actual mythology explanation and app description are introduced. This screen exists purely to set mood and branding, and no crow-detection logic runs here.



<img width="838" height="814" alt="About Screen" src="https://github.com/user-attachments/assets/a1c6dc03-1b81-4ec6-9194-c2e164634adf" />


This is the second screen in the site's flow, reached after clicking "Begin the enquiry" on the title screen, and it exists to explain the concept behind the project before the user reaches the actual upload form. It opens with a kicker line, "before you proceed," and the heading "What exactly is this?," signaling that this page is meant to set expectations. The page is split into two parts. The first, under the subheading "The belief this borrows from," gives a genuine, respectful summary of the real Hindu tradition it draws on — explaining that during Shraddha and the Pitru Paksha fortnight, crows are treated as emissaries of the Pitrs (departed ancestors), and that offering food to them (kaka bali) is believed to satisfy those ancestors, with a lingering crow near the house sometimes read in folk belief as a relative checking in. The second part, under "What we did with that belief," shifts into the site's own comedic premise, describing the website as a mock-official tool that assigns any uploaded crow photo a name, cause of death, and place of origin — explicitly clarifying that it is not a real genealogy or ornithology tool, just "a form with delusions of grandeur." A closing muted line warns the user, in the same deadpan humor, that their neighbourhood crow may turn out to be "a retired schoolteacher from Palakkad." The page ends with two navigation buttons: "Back," returning to the title screen, and "Continue to filing," which advances to the photo upload screen where the actual detection process begins.


<img width="1600" height="900" alt="Upload Screen" src="https://github.com/user-attachments/assets/0fab6b26-ee58-4978-be6f-a1b8c93f045e" />


This is the same upload/filing screen shown earlier — styled as mock government "form 7-K · photographic submission," with the heading "File a photograph for review" and the note that only one crow is permitted per submission, while pigeons, humans, and houseplants "will be noted and judged." Unlike the previous examples, this screenshot shows the screen in its **empty/initial state**: no photo has been uploaded yet, so the drop zone still displays its default prompt — a camera emoji, the instruction "Drop the photograph here, or tap to browse," and the hint "JPG or PNG. Karmic residue not required, but it helps." Below that is the same guidance note about submitting a clear, zoomed-in photo, followed by the collapsible "Terms, conditions, and other things nobody reads" disclaimer. The agreement checkbox is unchecked here, which is why the "Submit for karmic review" button appears greyed out and disabled — the form requires both a selected photo and a checked agreement box before submission is allowed. Only the "Back" button is active at this stage, letting the user return to the about screen.


<img width="915" height="1080" alt="Result Screen" src="https://github.com/user-attachments/assets/fb543fe8-b286-4275-a12b-f42f008a18c3" />


This is the final screen in the flow, shown only when the uploaded photo passes the crow-detection check, and it's styled as a formal "certificate of ancestral identification." At the top is a circular framed photo of the submitted crow, echoing the wax-seal/certificate aesthetic used throughout the site. Below the photo is a table of identifying details generated for that specific crow: its Name ("Ammini Iyer"), Age at death ("88 years"), Place of passing ("Kottayam"), and Cause of death ("Consumed one too many jackfruit chips") — all pulled from the site's persona-generation logic, which is seeded from the image itself so the same photo always produces the same identity on repeat uploads. Beneath that is a bar chart labeled "Sightings logged this week," showing how many times this specific crow has been identified across the days of the week (here, a single sighting on Sunday), with a note clarifying that this is a "shared ledger" — meaning the count includes sightings logged by other visitors to the site, not just this user. The page ends with an "Investigate another crow" button that resets the flow back to the upload screen, and a closing disclaimer reiterating the site's running joke: "Results are 0% accurate and not legally binding in any court, including celestial ones."


<img width="871" height="517" alt="Rejected Screen" src="https://github.com/user-attachments/assets/c0d28858-1fd9-4e79-bf2c-94d12c64ddc4" />


This is the screen shown when a submitted photo fails the crow-detection check — in this case, following the cat photo submitted on the previous upload screen. It displays a stamped, slightly tilted "No Departed Soul Detected" mark in red ink, mimicking a rejection stamp on an official document. Below the stamp is the specific rejection message generated for this submission: "This is a mammal, and by all appearances a fairly content one. This office deals exclusively in crows." — pulled from the mammal category in the detection logic's rejection-message set. The page ends with a "File a different photograph" button that returns the user to the upload screen to try again.
One thing worth flagging: the muted line underneath ("Please leave. Take the pigeon with you.") is actually hardcoded as a fixed line in the HTML rather than tied to the detected category — it was originally written specifically for the pigeon rejection case, so it doesn't quite make sense showing up under a cat rejection. If you'd like, I can fix this so that line either changes per category or gets removed for non-pigeon rejections.


# Diagrams


<img width="959" height="445" alt="Workflow" src="https://github.com/user-attachments/assets/112fbd48-9d70-49a5-9f18-6b60210025a2" />


This diagram illustrates the user journey through the Vamsha Vishakalanam website, from landing on the site to receiving a result. The flow begins at the **Title Screen**, where the user is introduced to the project name, and proceeds to the **About Screen**, which explains the mythology and premise behind the app. From there, the user reaches the **Upload Screen**, where they submit a photograph for review. Once submitted, the site moves into an **Analyzing** stage, representing the loading sequence where the photo is evaluated. Based on the outcome, the flow branches in one of two directions: if the photo is not identified as a crow, the user is taken to the **Rejected** screen, displaying the message "No Departed Soul Detected"; if it is confirmed as a crow, the user instead reaches the **Result** screen, showing the generated Ancestral Certificate with the crow's identity details. In both cases, the user is looped back to the Upload Screen, allowing them to submit another photograph and repeat the process.




## Team Contributions
- RESHMA.R : Worked on the core logic and content behind Vamsha Vishakalanam, building the crow detection pipeline that evaluates uploaded photographs, and the persona generation system that assigns each identified crow a name, age, place, and cause of death. She also wrote the mythology-based description of the project and the disclaimer, rejection, and result messaging that shape the site's tone throughout.
  
- VANDANA SUDEEP: Focused on the frontend design and development of Vamsha Vishakalanam, shaping the overall visual identity of the site. This included designing the page layouts for the title, about, upload, and result screens, establishing the ledger/certificate-style aesthetic used throughout, and implementing the CSS animations and visual details that give the site its distinct look and feel.


---
Made with ❤️ at TinkerHub Useless Projects 

![Static Badge](https://img.shields.io/badge/TinkerHub-24?color=%23000000&link=https%3A%2F%2Fwww.tinkerhub.org%2F)
![Static Badge](https://img.shields.io/badge/UselessProjects--26-26?link=https%3A%2F%2Ftinkerhub.org%2Fevents%2F1M8ORET9A1%2Fuseless-projects-3.0)



