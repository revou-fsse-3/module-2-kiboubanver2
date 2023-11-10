<h1 align='center'>Deployment Process, CI/CD, and Connect Domain To DNS Tutorial</h1>

## Introduction :alien:

This guide provides step-by-step instructions on how to connect a GitHub repository with Netlify, and connect a custom domain to your Netlify site. This will enabling automatic deployments for your web projects and create a branded and personalized web presence.

You can check the final product of this tutorial from this link: [kiboubanver2.net](https://kiboubanver2.site/)

## Table of Content :books:

##### 1. Connecting GitHub and Netlify :floppy_disk:

A. Prerequisites
B. Steps to Connect GitHub with Netlify
C. CI/CD using Netlify
D. Conclusion

##### 2. Custom Domain :globe_with_meridians:

A. Prerequisites
B. Steps to Create Custom Domain
C. Conclusion

---

## 1. Connecting GitHub and Netlify :floppy_disk:

### A. Prerequisites

Before proceeding, ensure the following:
a. [GitHub](https://github.com/) account.

### B. Steps to Connect GitHub with Netlify

a. Sign Up to [Netlify](https://www.netlify.com/) using your GitHub Account.
![Sign Up Netlify](/assets/Sign%20Up%20Netlify.png)

### C. CI/CD using Netlify

a. On the Netlify dashboard, click the "Add new site" button and choose "Import an existing project".
![Add new site](/assets/Add%20new%20site.png)

b. Select GitHub as the continuous deployment source.
![Deploy From Github](/assets/Deploy%20From%20Github.png)

c. Authorize Netlify to access your GitHub repositories.
![Authorized](/assets/Authorized.png)

d. Choose the repository you want to connect to Netlify.
![Connect Repo](/assets/Connect%20Repo.png)

e. Configure your settings, such as branch to deploy, build settings, and other deployment options. <em>Configure Build Settings (if required)</em>.

f. Deploy the Site
Once the settings are configured, initiate the first deployment by clicking the "Deploy site" button.
Netlify will build and deploy your site automatically.
![Deploy through Netlify](/assets/Deploy%20through%20Netlify.png)

### D. Conclusion

By connecting your GitHub repository to Netlify, you can automate the deployment process and easily manage updates for your web projects. This integration simplifies the deployment workflow, ensuring a seamless and efficient way to publish changes to your website.

---

## 2. Custom Domain :globe_with_meridians:

### A. Prerequisites

a. An existing website deployed on Netlify.
b. Ownership or access to a custom domain.

### B. Steps to Create Custom Domain

a. Go to [Niagahoster](https://www.niagahoster.co.id/) and click on "Domain," then select "Cari & Check Domain" from the dropdown menu.
![Niagahoster Dropdown](/assets/Niaga%20hoster%20dropdown.png)

b. Type in the domain name you desire and click "Cek Sekarang."
![Domain search](/assets/Domain%20search.png)

c. Niagahoster will check the availability of the site name and provide you with various domain name options based on your input.
![Domain Select](/assets/Domain%20select.png)

d. Select the one you prefer and proceed to payment, utilizing the various payment methods provided by Niagahoster.
![Domain puchase](/assets/Domain%20purchase.png)

e. After the purchase is completed, navigate to Netlify's overview page and click on "Domains."

f. Click the "Add or register domain" button on the top left side.
![Add domain](/assets/Add%20Domain%20to%20Netlify.png)

g. Enter your purchased domain in the box; Netlify will verify it for you. If it's available for use, the "Add Domain" button will appear.
![Add domain 2](/assets/Add%20Domain%20Netlify%202.png)

h. There will be an additional "Add DNS record" section, but you can proceed.
![DNS record](/assets/DNS%20Record.png)

i. Netlify will provide you with four domain names. Copy all of them.
![Netlify DNS](/assets/Netlify%20DNS.png)

j. Go to Niagahoster, access your purchased domain, and click "Manage."
![Manage domain](/assets/Manage%20Domain.png)

k. Navigate to DNS/Nameservers and update the name servers to the new ones provided by Netlify.
![DNS Mainservers](/assets/DNS%20:%20Name%20Servers.png)

l. Go to your deployed site page and click "Domain Management."
![Domain management](/assets/Domain%20Management.png)

m. Click "Add domain alias" After entering your domain, check the status. It usually takes around 3 to 24 hours before the new custom domain becomes active.
![Add domain alias](/assets/Add%20domain%20Alias.png)

### C. Conclusion

Connecting a custom domain to your Netlify site enhances your online presence and brand identity. By following these steps, you can seamlessly associate your domain with your Netlify-deployed website.
