<a name="readme-top"></a>
<br />
<div align="center">
  <a href="https://github.com/github_username/repo_name">
    <img src="meetplace.png" alt="Logo" width="200" height="200">
  </a>
<h3 align="center">Steramlit app that lets u chat with fake clients and generate performance plot and report using the API endpoints deployed on runpod</h3>

  <p align="center">
    project_description
    <br />
    <br />
    <br />
  </p>
</div>


<!-- ABOUT THE PROJECT -->
## About The Project

  This UI will help to create custom fake clients by inputing nice different attributes.


### Major steps done in this project

* Used the finetuned model and scoring algorithm from previous project
* Algorithm to input data to clients
* Creating difficulty levels
* Adjustable difficulty level
* Adding a translator head and a performance plot
* Deploying application as a docker image and hosting as an API endpoint on runpod

### Sales Techniques Identified by the algorithm
'BUILDING RAPPORT', 
'CREATING URGENCY', 'NEEDS ASSESMENT', 'SOCIAL PROOF',
                "CROSS SELLING OR UPSELLING","UPSELLING OR CROSS SELLING", 'VALUE BASED SELLING', 'OVERCOMING NEED OBJECTION','OVERCOMING TRUST OBJECTION','OVERCOMING PRICE OBJECTION','OVERCOMING TIME OBJECTION',
                'AWARE OF NEED','AWARE OF PROTECT INCOME','AWARE OF PROTECT FROM PAYMENT OBLIGATION','CLOSING POLICY',
                'NONE'

<!-- GETTING STARTED -->
## Getting Started

This is an example of how u can run the ui for the Custom fake clients.

### Prerequisites

cpu or gpu would be better

### Installation

1. Go to your terminal
2. Clone the repo  
   ```sh
   git clone https://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@github.com/Leulassaminew/insurance_plat.git
   ```
3. change to the cloned directory
   ```sh
   cd insurance_plat
   ```
4. Install requirements `requirements.txt`
   ```js
   pip install -r requirements.txt
   ```
5. Run the UI
   ```js
   streamlit run app1.py
   ```

   ```js
               on the UI you can choose desired difficulty level character and language as well
                --veryeasy    
                --easy
                --medium
                --hard
                --veryhard
   ```
    ```js
            You have 4 character options
                --char John (Phlegmatic and outgoing,works at google,lives in LA,degree in computer science)
                --char Anabal ( Sangiuine and calm,works at meetplace,lives in newyork,married and 4 kids)
                --char Keisha (Melancholic and analytical,works at fedex,lives in chicago,single mother with 2 kids)
                --char Stacy  (Choleric very rude and not interested in small talk,single works at microsoft,lives in seatle,rich)
   ```
   <img src="homepage.png" alt="Logo" width="800" height="400">   

   ```js
        *choose character,language and difficulty from the left side bar
        *Emotion of the client is displayed on the left bottom sidebar
        *After chatting on the uop left of the side bar u can change page to
                                      --Generate report on the performance
                                      --Generate performane plot
        *On the last option you can chat with dolly who is an Insurance assistantanswers questions related to 
   ```

