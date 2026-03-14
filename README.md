// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyBHhqzGNJhs64OR7D1xUVmcH7o5DGvMFsI",
  authDomain: "student-answer-website.firebaseapp.com",
  databaseURL: "https://student-answer-website-default-rtdb.asia-southeast1.firebasedatabase.app",
  projectId: "student-answer-website",
  storageBucket: "student-answer-website.firebasestorage.app",
  messagingSenderId: "598687788268",
  appId: "1:598687788268:web:49874a972ab04da23989c9",
  measurementId: "G-X066ZQNJX1"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);
