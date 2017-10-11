# Static-Website-On-AWS
A static demo website deployed on AWS 
Static websites deliver HTML, JavaScript, images, video and other files to your website visitors, and contain no application code. They are best for sites with few authors and relatively infrequent content changes, typically personal and simple marketing websites. Static websites are very low cost, provide high-levels of reliability, require almost no IT administration, and scale to handle enterprise-level traffic with no additional work.
# Step 1: Register a Domain
If you already have a registered domain, you can skip this step. If you are new to hosting a website, your first step is to register a domain, such as example.com, with a registrar of your choice.  
When you have a registered domain name, your next task is to create and configure Amazon S3 buckets for website hosting and to upload your website content.
# Step 2: Create and Configure Buckets and Upload Data
CREATE BUCKET
The bucket names must match the names of the website that you are hosting. For example, to host your example.com website on Amazon S3, you would create a bucket named example.com. To host a website under www.example.com, you would name the bucket www.example.com. In this example we will take www.example.com.
In this step, you sign in to the Amazon S3 console with your AWS account credentials and create the following bucket.

# To create your buckets and upload your website content for hosting

Sign in to the AWS Management Console and open the Amazon S3 console at https://console.aws.amazon.com/s3/.
Create buckets that matches your domain name. For instance,www.example.com.
Upload your website data to the www.example.com bucket.

# Configure permissions for your objects to make them publicly accessible.

Configure the permission by going to the your www.example.com bucket then Click permission, Under that click Bucket Policy
Copy the Policy from this git named policy.txt, Save it!

# Step 3: Configure Buckets for Website Hosting

When you configure a bucket for website hosting, you can access the website using the Amazon S3 assigned bucket website endpoint.

# To configure your buckets for website hosting
Sign in to the AWS Management Console and open the Amazon S3 console at https://console.aws.amazon.com/s3/.
-In the Bucket name list, choose the name of the bucket that you want to enable static website hosting for.
-Choose Properties.
-Choose Static website hosting.
-Configure the example.com bucket for website hosting. In the Index Document box, type the name that you gave your index page.
-Choose Save.

# Step 3.1: Test Your Endpoint
To test the website, type the URL of the endpoint in your browser.

