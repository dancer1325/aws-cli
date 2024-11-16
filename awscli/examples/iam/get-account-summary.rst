*
    aws iam get-account-summary

* allows
    * get information | current AWS account, about
        * IAM entity usage
        * IAM quotas

* _Example: sample output

Output::

    {
        "SummaryMap": {
            "UsersQuota": 5000,
            "GroupsQuota": 100,
            "InstanceProfiles": 6,
            "SigningCertificatesPerUserQuota": 2,
            "AccountAccessKeysPresent": 0,
            "RolesQuota": 250,
            "RolePolicySizeQuota": 10240,
            "AccountSigningCertificatesPresent": 0,
            "Users": 27,
            "ServerCertificatesQuota": 20,
            "ServerCertificates": 0,
            "AssumeRolePolicySizeQuota": 2048,
            "Groups": 7,
            "MFADevicesInUse": 1,
            "Roles": 3,
            "AccountMFAEnabled": 1,
            "MFADevices": 3,
            "GroupsPerUserQuota": 10,
            "GroupPolicySizeQuota": 5120,
            "InstanceProfilesQuota": 100,
            "AccessKeysPerUserQuota": 2,
            "Providers": 0,
            "UserPolicySizeQuota": 2048
        }
    }


* see `IAM and AWS STS quotas <https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_iam-quotas.html>`__ in the *AWS IAM User Guide*.