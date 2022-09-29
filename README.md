# sucre
##projet collaboratif 
#a faire : ajouter un ficher .gitignore
#Firebase :
// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyAENHPUfEoVXt7dTiDNNbZtY3qGPJe4iF4",
  authDomain: "base-e7e95.firebaseapp.com",
  projectId: "base-e7e95",
  storageBucket: "base-e7e95.appspot.com",
  messagingSenderId: "1010314331342",
  appId: "1:1010314331342:web:e1bdd70a1283bb3313fc9f",
  measurementId: "G-67W00N0F60"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);
