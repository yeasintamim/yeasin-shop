"# ecommerce-react" 
"# ecommerce-react" 
# yeasin-shop with react  | E-commerce react app
Simple ecommerce react js app with firebase [typescript].
![Firebase Deploy]

###



## Run Locally
### 1. Install Dependencies
```sh
$ npm install
```

### 2. Create a new firebase project
Login to your google account and create a new firebase project [here](https://console.firebase.google.com/u/0/)

Create an `env` file - Set filename`.env.prod` file for production and `.env.dev`for development and save it in the root of your project folder
and add the following configuration details. You can either use the same configuration details for both development and production but it's best to make separate projects. It can be found on your firebase project settings.

```
// SAMPLE CONFIG .env.dev, you should put the actual config details found on your project settings

FIREBASE_API_KEY=AIzaKJgkjhSdfSgkjhdkKJdkjowf
FIREBASE_AUTH_DOMAIN=yourauthdomin.firebaseapp.com
FIREBASE_DB_URL=https://yourdburl.firebaseio.com
FIREBASE_PROJECT_ID=yourproject-id
FIREBASE_STORAGE_BUCKET=yourstoragebucket.appspot.com
FIREBASE_MSG_SENDER_ID=43597918523958
FIREBASE_APP_ID=234598789798798fg3-034

``` 

After setting up necessary configuration,
create a **Database** and choose **Cloud Firestore** and start in test mode

### 3. Run development server
```sh 
$ npm run dev-server
```

---



## Build the project
```sh
$ npm run build
```

## Project is running at 
http://localhost:8080/

## How to add products or perform CRUD operations for Admin
1. Navigate to your site to `/signup`
2. Create an account for yourself
3. Go to your firestore collection `users collection` and edit the account you've just created. Change the role from `USER` to `ADMIN`.
4. Reload or sigin again to see the changes. 

**Firebase Admin to be integrated soon**

## Features

* Admin CRUD operations
* Firebase authentication
* Firebase auth provider authentication
* Account creation and edit

"# ecommerce-react" 
"# ecommerce-react" 

## Before adding product 
![screencapture-localhost-8080-2021-07-31-15_51_16](https://user-images.githubusercontent.com/61457979/127736304-11b98e97-01b7-4efb-bfde-264c10cfa833.png)
![featured product](https://user-images.githubusercontent.com/61457979/127736367-0b91dce9-4fef-41a3-a898-010876401fb4.PNG)



## After adding product
![main](https://user-images.githubusercontent.com/61457979/127736315-623438b0-e45f-4117-9f04-500073af7954.png)

## Basket or cart 
![1](https://user-images.githubusercontent.com/61457979/127736698-aa6ad240-dfe4-4280-8b56-a1af219b76c4.PNG)

![2](https://user-images.githubusercontent.com/61457979/127736623-84499ac7-2b30-4725-9799-72e54283740e.PNG)



## sign in and sign up 
![sign up](https://user-images.githubusercontent.com/61457979/127736344-b6ad0fab-1888-4274-b4dd-322519f9ff68.PNG)


## Admin panel
![admin](https://user-images.githubusercontent.com/61457979/127736531-43dbf070-7698-4b8c-8b02-2bc02a65eee7.PNG)
![admin panel product list](https://user-images.githubusercontent.com/61457979/127736536-52e02a06-5236-4bc2-8e78-968a2ed59f0d.PNG)
![add new product](https://user-images.githubusercontent.com/61457979/127736538-c804a2a4-d3e9-4894-abf8-9ec9c5821878.PNG)

## firebase database screen shots
![firebase](https://user-images.githubusercontent.com/61457979/127737661-79f5a6e5-5ec1-4dab-89f2-33d0acf63cd9.PNG)
![fir2](https://user-images.githubusercontent.com/61457979/127737663-0b9f7cb3-ec18-412a-b1c5-54334580cf4f.PNG)
