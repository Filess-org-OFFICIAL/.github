## Filess 👋


Welcome to Filess! Filess is the best platform for asset sharing and storing, putting the YOU into your files. Seamlessly upload images, videos, PDFs, your entire computer's C: drive and more! Filess provides you with a large amount of *free* data storage and with the tools you need to rename, tag, and customize your shareable link. 

<img width="292" alt="filessDemoLink" src="https://user-images.githubusercontent.com/86496017/180121165-1e790549-db4e-4898-8f40-a094a7fe4e1a.PNG">

Once you have a file uploaded, simply click on it to view its details along with a copy button to share with your thousands of friends in seconds. You can even purchase more space and further customization features if you also want to share your grandma's full disk.

<img width="956" alt="filessDashboard" src="https://user-images.githubusercontent.com/86496017/180121117-d385b6aa-b161-4b9b-8be7-ed7259474dee.PNG">

Filess V1 was finally released into production in July of 2022, after a couple months of Beta and development. The project idea was thanks to @max_prihodk0 who helped co-start it. The project is built on the Flask framework with both the website and postgres database hosted by Heroku. Files are stored in an ACL regulated AWS S3 bucket and email verification is established through Google's OAuth2 API.


<img width="378" alt="filessLogin" src="https://user-images.githubusercontent.com/86496017/180121179-3fac77ba-86b4-4fd8-8027-25e1125312ca.PNG">

This is a public release of the website, meaning that sensitive data such as OAuth2 credential files and certain keys were removed. Feel free to look around at the website's structure and logic, however. Cheers!

-Mason
