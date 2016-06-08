# ebs-backup
1. Create a document with the following code.
2. Use iam create-role CLI command to associate the trust with the ebs-backup role.
`aws iam put-role-policy --role-name snapshot-trust.json --policy-name TakeSnapshots --policy-document file://snapshot-policy.json`
3. Create a Python Lambda function using the ebs-backup.py code.  

