+++
title = "Check Template Outputs"
chapter = false
weight = 230
+++

## Login to the AWS Console

1. From the [Event Engine dashboard](https://dashboard.eventengine.run/) click login to AWS console
2. Navigate to the CloudFormation console in us-east-1 (N. Virginia)
3. Change the filter to view **Deleted** stacks
3. Select the top stack ( they are ordered by creation date)
4. Click on the **"Outputs"** tab

Notice that the values for the **LicenseToken** parameter has been replaced with the value 
specified in the global override.

Notice that the value for **AvailablityZones** has been replaced with 2 AZ names from the 
us-east-1 region.

![fig1.4](/images/stack_outputs.png)

