# breast-cancer-diagnosis

This is a project aiming to predict the risk of breast cancer in women.

After exploring applications that estimate the risk of breast cancer, I found two applications on the Google Play Store and none in the Cafe Bazzar store.

I discovered some relevant papers about data mining and its use in breast cancer diagnosis, which are uploaded to this repository.

##### Features of this project:
1: A backend service to store and send JSON files, which is used to generate dynamic forms.

2: A backend service to store and send user data, returning the risk to the user.

3: A frontend app for Android devices that utilizes the JSON file to generate dynamic forms and displays the risk of cancer to users.

4: A data mining method to preprocess, classify, and predict the risk of cancer using local and foreign breast cancer data.

5: A paper to determine and identify the best method of data mining for this specific task, increasing the accuracy of prediction.

### 1: Json storage backend service

this backend service consists of a storage and post, get, del methods to recive and send the json files

### 2: App backend service

this backend service gets the user data and after saving it returns the risk

### 3: The Android App

this android app uses the json file from the first backend service to draw the form which user should complete. the data will be sent to the second service to be processed the returnd amount of risk will be shown to the user and the proper instructions will be given

### 4: The Data Mining Method

this method should be accurate enough so after reading the papers and selecting the best method and increasing the accuracy it should be applied to the data sets

### 5: The Review Paper

this paper will be a review of the selected papers in this repo it will show the method chosen for this project and its advantages over other methods and the outcome


# Todo:
- [ ] read the review papers related to the task
- [ ] implement the backend services using golang 
- [ ] find related data sets and upload them to this repo
- [ ] search for cancer facilities to get some local data
- [ ] applay some known mothods to data sets and compare them
- [ ] implement the android app
- [ ] dockerize the backend services
- [ ] find an expert to get details about breast cancer
