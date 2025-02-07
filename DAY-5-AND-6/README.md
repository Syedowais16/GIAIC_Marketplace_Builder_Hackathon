# **E-Commerce System - Testing Report**

## **Overview**
This repository contains the testing report for the E-Commerce System. The testing covers functional, performance, security, and compatibility aspects of the system. The key focus areas include product listing, cart functionality, checkout, wishlist, search, filters, API handling, performance optimization, security measures, and the review & rating system.


## **Table of Contents**
- [Introduction](#introduction)
- [Scope](#scope)
- [Test Approach](#test-approach)
- [Test Environment](#test-environment)
- [Test Case Execution Summary](#test-case-execution-summary)
- [Detailed Testing Analysis](#detailed-testing-analysis)
  - [Functional Testing](#functional-testing)
  - [Performance Testing](#performance-testing)
  - [Security Testing](#security-testing)
  - [Compatibility Testing](#compatibility-testing)
- [Review & Rating Feature Testing](#review--rating-feature-testing)
- [Defects Found](#defects-found)
- [Conclusion](#conclusion)
- [Future Enhancements](#future-enhancements)
- [Author](#author)


## **Introduction**
The goal of this testing process was to validate the functionalities of an E-Commerce System. The system includes product listing, shopping cart, checkout, wishlist, search, filtering, and a review & rating feature. The objective was to ensure that the system performs correctly, efficiently, and securely under various conditions.


## **Scope**
The scope of this testing includes:

- **Functional Testing**: Verifying all core functionalities, including product management, checkout, wishlist, search, and reviews.
- **Performance Testing**: Checking system response times, load handling, and review section performance.
- **Security Testing**: Ensuring secure data handling and preventing vulnerabilities.
- **Compatibility Testing**: Testing across multiple devices and browsers.


## **Test Approach**
- **Manual Testing**: All test cases were executed manually to ensure system behavior is as expected.
- **Black Box Testing**: Only inputs and outputs were analyzed without inspecting the source code.
- **Regression Testing**: Ensuring that newly added features do not break existing functionality.


## **Test Environment**
- **Operating Systems**: Windows 10
- **Browsers Tested**: Google Chrome, Mozilla Firefox, Safari, Microsoft Edge
- **Devices Tested**: Desktop, Mobile (Android)
- **Internet Speed**: 1 Mbps


## **Test Case Execution Summary**

| **Test Case ID** | **Test Case Description** | **Status** | **Severity** |
|---------------|-------------------------|----------|------------|
| TC-001 | Product Listing Loads Successfully | ✅ Passed | Low |
| TC-002 | Product Fetching from API | ✅ Passed | Low |
| TC-003 | Cart Add Functionality | ✅ Passed | Medium |
| TC-004 | Cart Remove Functionality | ✅ Passed | Medium |
| TC-005 | Checkout Process | ✅ Passed | High |
| TC-006 | Wishlist Add Functionality | ✅ Passed | Medium |
| TC-007 | Wishlist Remove Functionality | ✅ Passed | Medium |
| TC-008 | Search Bar Functionality | ✅ Passed | Low |
| TC-009 | Filter Panel - Availability Filter | ✅ Passed | Low |
| TC-010 | Filter Panel - Price Range | ✅ Passed | Low |
| TC-011 | API Failure Handling (Product Fetch) | ✅ Passed | High |
| TC-012 | Performance Testing - Load Time | ✅ Passed | Medium |
| TC-013 | Cross-Browser Testing | ✅ Passed | Medium |
| TC-014 | Mobile Responsiveness | ✅ Passed | Medium |
| TC-015 | Submit Product Review | ✅ Passed | Medium |
| TC-016 | Persistent Review Storage | ✅ Passed | High |
| TC-017 | Display Username with Review | ✅ Passed | Medium |
| TC-018 | Rating Calculation | ✅ Passed | High |
| TC-019 | Display of Average Rating | ✅ Passed | Medium |
| TC-020 | Multiple Reviews for a Single Product | ✅ Passed | Medium |
| TC-021 | Review Submission with Empty Fields | ✅ Passed | High |
| TC-022 | Performance Test for Review Loading | ✅ Passed | Medium |


## **Detailed Testing Analysis**

### **Functional Testing**
✅ **Product Listing**: Products load successfully within **1.1 seconds**.  
✅ **Cart Management**: Products can be added and removed correctly, with the cart count updating accurately.  
✅ **Checkout Process**: The checkout process functions without errors, allowing successful order placement.  
✅ **Wishlist Feature**: Products are correctly added and removed from the wishlist.  
✅ **Search Functionality**: The search bar retrieves relevant products as expected.  
✅ **Filtering Options**: Availability and price range filters work correctly.  


### **Performance Testing**
✅ **Homepage Load Time**: **1.1 seconds** (Expected: <2 seconds).  
✅ **API Response Time**: **1.1 seconds** (Expected: <2 seconds).  
✅ **Review Section Load Time**: **1.2 seconds**.  


### **Compatibility Testing**
✅ **Cross-Browser Support**: No UI issues on Chrome, Firefox, Safari, or Edge.  
✅ **Mobile Responsiveness**: The system is fully responsive across different screen sizes.  


## **Review & Rating Feature Testing**

### **Execution Details**
The review & rating system was tested on various aspects:  
- ✅ Users can **submit a review and rating**.  
- ✅ Reviews **persist after page refresh**.  
- ✅ **Username is displayed** alongside reviews.  
- ✅ The system **calculates the average rating correctly**.  
- ✅ Multiple reviews from different users appear correctly.  
- ✅ Empty reviews are **blocked with validation messages**.  

### **Results**
- ✅ **Average Rating Calculation**: Updates accurately after each review.  
- ✅ **Persistent Storage**: Reviews remain visible even after session refresh.  
- ✅ **Performance**: Reviews load within **1.2 seconds**.  


## **Defects Found**
🚀 **No major defects found**.  
🔹 **Minor UI improvement suggested** for better alignment of the review display section.  


## **Conclusion**
- **All test cases passed successfully**.  
- The system is **stable, responsive, and secure**.  
- **Performance meets expectations**, with fast load times.  
- **Security measures are effective**, preventing vulnerabilities.  
- **Review & Rating System functions correctly** with persistent storage and average rating calculation.  

