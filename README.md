# MiriNail

<p align="center">
  <img src="./image/mirinail.png" alt="MiriNail Logo" width="number" />
</p>

<br><br>

## One-Line Summary

### **An AR-powered nail fitting service with NFT integration**

<br><br>

## Background & Motivation

- The booming nail care market  
- Customers who aren’t satisfied after getting their nails done  
- Nail salons struggling to attract new clients  
- Lack of awareness around nail design copyright  

<br><br>

## Project Intent

- Provide a service that connects customers and designers in the growing nail market  
- Offer customers the ability to choose nail art designs that match their tastes  

<br><br>

## Key Features

- **Designer & Community Pages:** Smooth communication channels between customers and designers  
- **AR Nail Fitting:** Real-time fitting of chosen nail art designs on users’ own nails via AR  
- **NFT for Nail Art:** Designers’ nail art is minted as NFTs using blockchain technology  

<br><br>

## Project Team

<p align="center">
  <img src="./image/team.png" alt="Team Photo" width="number" />
</p>

<br><br>

## Project Timeline

### April 11, 2022 ~ May 20, 2022 (6 weeks)

<br><br>

## Collaboration Tools

- Jira  
- MatterMost  
- GitLab  
- [Notion](https://www.notion.so/MIRINAIL-33e8f8a0c76f4aed8a8e2f6998be4300)  

<br><br>

## System Architecture

<p align="center">
  <img src="./image/architecture.jpg" alt="Service Architecture Diagram" width="number" />
</p>

<br><br>

# Main

## Home Page

<p align="center">
  <img src="/image/main.gif" alt="Main Page GIF" width="number" />
</p>

1. The home page shows popular nail art, top designers, and highlights from the community pages.  

<br><br>

## Search (NavBar)

<p align="center">
  <img src="/image/search.gif" alt="Search GIF" width="number" />
</p>

1. Use the search box in the navbar to look up designers.  
2. From the results, visit a designer’s page to see their updates or send inquiries.  

<br><br>

# Nail Art

## Nail Art List

<p align="center">
  <img src="/image/naillist.gif" alt="Nail Art List GIF" width="number" />
</p>

1. Navigate to the nail art list via the navbar.  
2. The initial view displays all nail art with pagination for browsing.  
3. Filter by type or color at the top for broad categorization.  
4. “Type” filter offers three categories, sortable by newest or most popular.  
5. “Color” filter offers 12 colors, also sortable by newest or most popular.  

<br><br>

## Nail Art Details

<p align="center">
  <img src="/image/naildetail.gif" alt="Nail Art Detail GIF" width="number" />
</p>

1. Select a nail art from the list to see its detail view.  
2. View name, price, designer, and description.  
3. Click “Try in AR” to preview the design on your own nails.  
4. Click “Book Now” to schedule an appointment for your preferred date.  
5. “Like” a design to add it to your favorites.  
6. Browse other works by the same designer.  
7. Read customer reviews for the selected nail art.  
8. Send a one-on-one inquiry about this design.  

<br><br>

## Booking Flow

<p align="center">
  <img src="./image/reservation.gif" alt="Reservation GIF" width="number" />
</p>

1. From the detail page, click the “Book” button to go to the reservation page.  
2. Select a date on the calendar to see available time slots.  
3. Choose your slot, enter any special requests, and confirm your booking.  

<br><br>

## AR Nail Fitting

<p align="center">
  <img src="./image/AR.gif" alt="AR Fitting GIF" width="number" />
</p>

1. Click “Try in AR” on the detail page to open the fitting window.  
2. Hold your hand up; the app recognizes your nails and overlays the selected design in real time.  

<br><br>

# Designers

## Designer Directory

<p align="center">
  <img src="./image/designerList.gif" alt="Designer List GIF" width="number" />
</p>

1. The directory is divided into themed view and full list.  
2. In “Themed,” sort designers by popularity, recency, or rating.  
3. In “All,” browse every registered designer.  
4. Click on any designer to visit their profile page.  

<br><br>

# My Page

## User Profile

<p align="center">
  <img src="./image/mypage_user.gif" alt="User My Page GIF" width="number" />
</p>

1. View your own activity and history.  
2. Check your upcoming and past reservations.  
3. In “History,” see your liked nail art, posts, reviews, and inquiries.  
4. View the list of designers you follow.  

<br><br>

## Designer Registration

<p align="center">
  <img src="./image/designerRegister.gif" alt="Designer Registration GIF" width="number" />
</p>

1. From your My Page, apply to become a designer.  
2. Provide your designer name, contact info, address, and attach a business license.  

<br><br>

# Designer Tools

## Nail Art Submission

<p align="center">
  <img src="./image/register.gif" alt="Register Nail Art GIF" width="number" />
</p>

1. Upload a thumbnail image and AR fitting image for the nail art.  
2. Enter nail type, color, shade, price, and description.  
3. Upon submission, IPFS hashes are generated and recorded on the blockchain.  

<br><br>

## News & Updates

<p align="center">
  <img src="./image/new.gif" alt="Post News GIF" width="number" />
</p>

1. Designers can post announcements to be seen by users on their page.  
2. Enter a title, upload one or more images, write content, and publish.  

<br><br>

## Inquiries Management

<p align="center">
  <img src="./image/qna.gif" alt="Q&A Management GIF" width="number" />
</p>

1. View all incoming user inquiries.  
2. Reply directly to each inquiry.  

<br><br>

# Admin

<p align="center">
  <img src="./image/admin.gif" alt="Admin Dashboard GIF" width="number" />
</p>

1. Admins can approve or reject designer registration applications.  

<br><br>

# Community

<p align="center">
  <img src="./image/community.gif" alt="Community Page GIF" width="number" />
</p>

1. Browse posts from other users.  
2. Click on posts to read and comment.  
3. Create a new post by uploading images and writing content.  

<br><br>

# GPU Server Setup

## 1. Install Graphics Drivers

```bash
$ ubuntu-drivers devices
