# Working with Stacks<a name="stacks"></a>

A stack is a collection of AWS resources that you can manage as a single unit\. In other words, you can create, update, or delete a collection of resources by creating, updating, or deleting stacks\. All the resources in a stack are defined by the stack's AWS CloudFormation template\. A stack, for instance, can include all the resources required to run a web application, such as a web server, a database, and networking rules\. If you no longer require that web application, you can simply delete the stack, and all of its related resources are deleted\.

AWS CloudFormation ensures all stack resources are created or deleted as appropriate\. Because AWS CloudFormation treats the stack resources as a single unit, they must all be created or deleted successfully for the stack to be created or deleted\. If a resource cannot be created, AWS CloudFormation rolls the stack back and automatically deletes any resources that were created\. If a resource cannot be deleted, any remaining resources are retained until the stack can be successfully deleted\.

You can work with stacks by using the AWS CloudFormation [console](https://console.aws.amazon.com/cloudformation/), [API](http://docs.aws.amazon.com/AWSCloudFormation/latest/APIReference/), or [AWS CLI](http://docs.aws.amazon.com/cli/latest/reference/cloudformation)\.

**Note**  
You are charged for the stack resources for the time they were operating \(even if you deleted the stack right away\)\.


+ [Using the AWS CloudFormation Console](cfn-using-console.md)
+ [Using the AWS Command Line Interface](cfn-using-cli.md)
+ [AWS CloudFormation Stacks Updates](using-cfn-updating-stacks.md)
+ [Exporting Stack Output Values](using-cfn-stack-exports.md)
+ [Listing Stacks That Import an Exported Output Value](using-cfn-stack-imports.md)
+ [Working with Nested Stacks](using-cfn-nested-stacks.md)
+ [Working with Microsoft Windows Stacks on AWS CloudFormation](cfn-windows-stacks.md)