// Import the functions you need from the SDKs you need

import { initializeApp } from "firebase/app";

import { getAnalytics } from "firebase/analytics";

// TODO: Add SDKs for Firebase products that you want to use

// https://firebase.google.com/docs/web/setup#available-libraries


// Your web app's Firebase configuration

// For Firebase JS SDK v7.20.0 and later, measurementId is optional

const firebaseConfig = {

  apiKey: "AIzaSyBbEXChOOEczW99wIFF2NiPtXAgOjE3K4Y",

  authDomain: "superchat-96168.firebaseapp.com",

  projectId: "superchat-96168",

  storageBucket: "superchat-96168.appspot.com",

  messagingSenderId: "371421721681",

  appId: "1:371421721681:web:75bf5a136242c2b5ca3470",

  measurementId: "G-DEX02ENDM0"

};


// Initialize Firebase

const app = initializeApp(firebaseConfig);

const analytics = getAnalytics(app);