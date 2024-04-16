# Question-Answer-Retrieval
This project uses [Mistral-7B](https://huggingface.co/TheBloke/Mistral-7B-Instruct-v0.1-GGUF/blob/main/mistral-7b-instruct-v0.1.Q4_K_S.gguf) model to generate Question and Answers from a PDF and gives output in a CSV file and on the terminal.

## Steps to run the code:
1. **Download the code:** 
   - Clone the repository or download the code as a ZIP file.
     
2. **Navigate to the directory:** 
   - Use Annaconda CLI to navigate to the directory where the code is located.
     
3. **Create a conda environment and activate it**
   - Refer to [commands.txt](https://github.com/craterr/Question-Answer-Retrieval/blob/main/commands.txt)

3. **Install dependencies:**
   -  ```
      pip install -r requirements.txt
      ```

4. **Run the code:** 
   - Execute the command to run the code. 
     ```
     python app.py
     ```
   - Start the server
     ```
     uvicorn app:app --reload
     ```
5. **Open localhost:8000 and upload the desired pdf and generate😀**

## Project Preview
[localhost:8000](http://localhost:8000)
![image](https://github.com/craterr/Question-Answer-Retrieval/assets/106965125/fc3db877-7ec8-476e-80e1-befa6831ae77)

![image](https://github.com/craterr/Question-Answer-Retrieval/assets/106965125/05ac61d9-3d9b-4db5-bdfe-a8b023318def)

![image](https://github.com/craterr/Question-Answer-Retrieval/assets/106965125/fd9b7752-94b2-4c93-85a2-648bc72557df)
Click on download button to download the csv file else it will be saved [here](https://github.com/craterr/Question-Answer-Retrieval/tree/main/static/output).

![image](https://github.com/craterr/Question-Answer-Retrieval/assets/106965125/d6ddedb1-65a2-49e3-a851-856237787f0f)

