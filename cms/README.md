# CMS for MH photography portfolio

This is a content management system to manage a professional photographer's portfolio. The client can add, delete, or manage different essential sections of his portfolio.

Media is stored and hosted on Cloudinary. the CMS manages media by uploading it to [cloudinary](https://cloudinary.com/)'s API which then returns the URL to the uploaded media, then the URL is sent to the backend and stored using MongoDB.

Continuously intergrated and deployed on [Netlify](https://www.netlify.com/)

## Usecases
- Sign-in, forgot password, reset passord
- Manage CMS account
- Add/Delete gallery to the portfolio
- Client can change the order of the galleries (position of the each gallery in the portfolio)
- Add/Delete images in a gallery
- Change gallery name
- Update about image, CV link, introduction text
- Update phone number/email/social links..
- Update portfolio home page introduction video

## Main technologies used
- ReactJs
- Redux
- Styled components
- Cloudinary

You can view or test the usecases of the CMS using the demo [here](https://mh-cms-demo.netlify.app/), use this email and password to sign in, 
- demo@gmail.com 
- Demo123#

[Link to the demo CMS (use the above demo account)](https://mh-cms-demo.netlify.app/) [mh-cms-demo.netlify.app].  

[Link to the actual CMS (authorized access to client only)](https://mh-cms.netlify.app/) [mh-cms.netlify.app]. 
