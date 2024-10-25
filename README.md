"# TX03_CAC_2024_25_submission" 


1. The project includes two main files, one is a python code, which is embedded in the python notebook.  It uses GRU model to detect FOG using acceleration data from MIT app Inventor. The notebook was runnable in Kaggle, the data science platform.
2. Second file is a MIT app inventor file. aia, which use the phone accelerometer to detect the motion and send the acceleration to Kaggle, and also receive the FOG prediction from Kaggle
3. The Communication between Kaggle and MIT App inventor goes through NGROK and http server via Flask API.
4. The program requires NGROk authentication key to run the communication. The key can be generated from https://ngrok.com
5. The authentication key needs to be copied to the python code where NGROK key was required.
6. The NGROK tunnel URL needs to be copied to MIT app inventor to enable the communication prior to the MIT app inventor code operation.