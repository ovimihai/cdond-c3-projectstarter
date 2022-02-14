# Give Your Application Auto-Deploy Superpowers

* [REVIEW](https://review.udacity.com/)
* [CODE REVIEW ](https://review.udacity.com/)
* [HISTORY](https://review.udacity.com/)

## Meets Specifications

You have nailed it ![:clap:](https://review.udacity.com/assets/images/emojis/clap.png) ![:raised_hands:](https://review.udacity.com/assets/images/emojis/raised_hands.png)  
Congratulations on completing this hard project ![:fire:](https://review.udacity.com/assets/images/emojis/fire.png) ![:tada:](https://review.udacity.com/assets/images/emojis/tada.png)  
As per your work so far, you won't take much time completing any future project ![:star:](https://review.udacity.com/assets/images/emojis/star.png) ![:star2:](https://review.udacity.com/assets/images/emojis/star2.png)  
All the best for future projects, keep learning and stay udacious ![:udacious:](https://review.udacity.com/assets/images/emojis/udacious.png)

##### COMMENTS

* Fantastic job done in the submission
  * Great work with the Presentation.
  * Backend and Frontend are build, tested and analyzed perfectly![:v:](https://review.udacity.com/assets/images/emojis/v.png)
  * Frontend and Backend service are up and working perfectly![:ok_hand:](https://review.udacity.com/assets/images/emojis/ok_hand.png)
  * Nice work setting up Prometheus Service![:clap:](https://review.udacity.com/assets/images/emojis/clap.png)![:fire:](https://review.udacity.com/assets/images/emojis/fire.png)
* I hope you have definitely learned something new from this project ![:raised_hands:](https://review.udacity.com/assets/images/emojis/raised_hands.png)
* Although the project is complete, feel free to reach out to the mentors via [Knowledge Udacity](https://knowledge.udacity.com/) platform to get any help you think you need ![:raised_hands:](https://review.udacity.com/assets/images/emojis/raised_hands.png) We will be more than happy to help you![:v:](https://review.udacity.com/assets/images/emojis/v.png)

##### RESOURCES

Below are some links to a few things to look for while working in CircleCI and Ansible

* [Tips and tricks CircleCI](https://circleci.com/blog/six-optimization-tips-for-your-config/)
* [Tips and Tricks Ansible](https://blog.ippon.tech/ansible-tips-and-tricks/)

## Section 1: Selling CI/CD to your Team/Organization

The CI/CD benefits proposal contains essential benefits of CI/CD, and describes the business context that will benefit from the automation tools. Explanation should include benefits that translate to revenue and cost for the business.

This rubric has already been approved in the previous review![:v:](https://review.udacity.com/assets/images/emojis/v.png)

## Section 2: Deploying Working, Trustworthy Software

A public git repository with your project code. \[URL01\]

Evidence of code-based CI/CD configuration in the form of yaml files in your git repository.

Console output of various pre-deploy job failure scenarios:

* Build Jobs that failed because of compile errors. \[SCREENSHOT01\]
* Failed unit tests. \[SCREENSHOT02\]
* Failure because of vulnerable packages. \[SCREENSHOT03\]
* An alert from one of your failed builds. \[SCREENSHOT04\]

Evidence in your code that:

* Compile errors have been fixed.
* Unit tests have been fixed.
* All critical security vulnerabilities caught by the "Analyze" job have been fixed.

This rubric has already been approved in the previous review![:v:](https://review.udacity.com/assets/images/emojis/v.png)

Console output of appropriate failure for infrastructure creation job (using CloudFormation). \[SCREENSHOT05\]

Console output of a smoke test job that is failing appropriately. \[SCREENSHOT06\]

Console output of a successful rollback after a failed smoke test. \[SCREENSHOT07\]

Console output of successful promotion of new version to production in CloudFront. \[SCREENSHOT08\]

Console output of successful cleanup job that removes old S3 bucket and EC2 instance. \[SCREENSHOT09\]

Evidence that the deploy jobs only happen on the `master` branch. \[SCREENSHOT10\]

Evidence of deployed and functioning front-end application in an S3 bucket \[URL02\].

Evidence of deployed and functioning front-end application in CloudFront. \[URL03\_SCREENSHOT\]

Evidence of healthy back-end application. \[URL04\_SCREENSHOT\]

7) ![:white_check_mark:](https://review.udacity.com/assets/images/emojis/white_check_mark.png) Evidence of deployed and functioning front-end application in an S3 bucket \[URL02\]  
[![13_bucket.png](https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/86334/1644752024/13_bucket.png)](https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/86334/1644752024/13_bucket.png)

---

8) ![:white_check_mark:](https://review.udacity.com/assets/images/emojis/white_check_mark.png) Evidence of deployed and functioning Frontend in CloudFront. \[URL03\]  
[![13_cloudfront.png](https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/86334/1644752024/13_cloudfront.png)](https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/86334/1644752024/13_cloudfront.png)

##### NOTE

Every other point in this rubric was already passed in the previous review![:v:](https://review.udacity.com/assets/images/emojis/v.png)

## Section 3: Turn Errors into Sirens

Evidence of Prometheus Server. \[URL05\_SCREENSHOT\].

Evidence that Prometheus is monitoring memory, cpu and disk usage of EC2 instances. \[SCREENSHOT11\]

Evidence that Prometheus and AlertManager send alerts when certain conditions exist in the EC2 instance. \[SCREENSHOT12\]

This rubric has already been approved in the previous review![:v:](https://review.udacity.com/assets/images/emojis/v.png)