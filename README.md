# tf-aws-s3-policy-test
Test of S3 bucket lifecycle exclusion policies

# Original request , ticket 30366

..Trying to create a lifecycle rule on s3 bucket with an exclusion approach.
Example, in my bucket test1 i have multiple subdirectories sub1, sub2, sub3 etc...

In my sub1 i have other subdirectories: sub1A1, sub1A2 and sub1A3
I want to add delete policie for 90 days on all my bucket test1.
But i want to preserve sub1A1 and sub1A2 of deletion

We must keep in mind that in sub1 there will be later new files and subdirectories.
But i want to always preserve sub1A1 and sub1A2

# TODO

- [x] init reference 
- [ ] create teast code
