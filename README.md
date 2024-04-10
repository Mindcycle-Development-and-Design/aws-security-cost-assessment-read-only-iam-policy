# aws-security-cost-assessment-read-only-iam-policy
A policy document for providing read only access to key aws cost and security management services. This extends the AWS managed read-only policy.

## How to use
Attach this policy to any user, role, or group that requires read only access to all aws services, as well as key cost and security services like AWS budgets, trusted advisor, guard duty, cloudtrail etc. The policy should be used in addition the AWS Managed ReadOnlyAccess policy.

1. Create an IAM user, group, or role
2. Attach the AWS Managed ReadOnlyAccess policyy
3. Attach this policy as an inline or custom policy

# Issues

If you find any issues or have requests to improve this policy please submit that via the issues feature. We will do our best to address them as soon as possible.
