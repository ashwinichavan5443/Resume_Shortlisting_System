# Resume_Shortlisting_System
Our Resume Shortlisting System leverages the power of OpenAI's state-of-the-art technology to revolutionize the way you manage candidate applications. This cutting-edge system automates the often tedious and time-consuming task of reviewing resumes, ensuring that you identify the best candidates efficiently and without bias.

## </b>Resume Shortlisting System </b>
This project this divided into three functions:<br>
**Function 1: pdf_to_img(invoice_path)**</br>
<u>Purpose</u></br>
The **pdf_to_img** function is responsible for converting each page of a PDF invoice into an image format. This conversion is a crucial step in the subsequent text extraction process.

<u>Parameters</u></br>
**invoice_path** (string): The path to the PDF invoice file that needs to be converted into images.

**Function 2: img_to_text(image_path)**</br>
<u>Purpose</u></br>
The **img_to_text** function is responsible text extraction from invoice image 

<u>Parameters</u></br>
**image_path** (string): The path to the image invoice file for text extraction from image.

**Function 3: invoice_shortlisting(invoiceText, jobDescription):**</br>
<u>Purpose</u></br>
The **invoice_shortlisting** function is a crucial component of the application's workflow. Its primary purpose is to utilize the OpenAI completion API to evaluate candidates for a specific job based on the extracted resume text and the job description.</br>
<u>Parameters</u></br>
**invoiceText** (string): The extracted invoice text.</br>

**jobDescription** (string): We can passed the required job description.


Here's a general guide on how to create an API key for OpenAI APIs:

Sign Up or Log In: If you don't already have an OpenAI account, sign up for one at the OpenAI website. If you have an account, log in.

Navigate to API Dashboard: Once you're logged in, go to the OpenAI API dashboard or a similar section where you can manage your API keys. This dashboard may look different depending on any updates that have occurred since my last knowledge update.

Create a New API Key:

Look for an option to "Create API Key" or similar wording.
Click on this option to initiate the process.
Configure Permissions and Restrictions:

You may be asked to configure the permissions and restrictions for the API key.
Common options include specifying which API(s) the key can access, rate limits, and any IP address restrictions.
Generate the API Key:

Once you've configured the settings to your requirements, generate the API key.
The system will typically provide you with a unique API key that you'll use to authenticate your requests.
Store Your API Key Securely: It's crucial to keep your API key secure. Do not share it in public repositories or with unauthorized individuals. Consider using environment variables or a secure configuration management system to store your API key.

Integrate the API Key: You can now integrate the API key into your applications or scripts to make authenticated requests to OpenAI APIs.
#ContributorFriendly #DeepLearning #NaturalLanguageProcessing #chatgpt #openAI #API #OpenSource #FirstTimersOnly

