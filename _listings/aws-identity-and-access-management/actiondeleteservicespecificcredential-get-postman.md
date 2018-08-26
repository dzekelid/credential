{
  "info": {
    "name": "AWS Identity and Access Management API Delete Service Specific Credential",
    "_postman_id": "7240c3f6-4c30-4a46-b2fc-75b3c36a412e",
    "description": "Deletes the specified service-specific credential.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "OpenID Connect Providers",
      "item": [
        {
          "id": "c6815c48-b52f-4c4b-926d-985a623b1bd2",
          "name": "addClientIDToOpenIDConnectProvider",
          "request": {
            "url": "http://example.com/api/?Action=AddClientIDToOpenIDConnectProvider?ClientID=ClientID&OpenIDConnectProviderArn=OpenIDConnectProviderArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds a new client ID (also known as audience) to the list of client IDs already\n      registered for the specified IAM OpenID Connect (OIDC) provider resource."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "afce70ea-8000-46b7-9119-e8d720d41009"
            }
          ]
        },
        {
          "id": "cfaf7e54-7875-4a38-9f46-9a4043988112",
          "name": "createOpenIDConnectProvider",
          "request": {
            "url": "http://example.com/api/?Action=CreateOpenIDConnectProvider?ClientIDList.member.N=ClientIDList.member.N&ThumbprintList.member.N=ThumbprintList.member.N&Url=Url",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an IAM entity to describe an identity provider (IdP) that supports."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6f4389b0-ad99-4d3e-bc24-05f94d44740b"
            }
          ]
        },
        {
          "id": "2f2fa909-c34f-44b6-b457-3d62e0e0bc64",
          "name": "deleteOpenIDConnectProvider",
          "request": {
            "url": "http://example.com/api/?Action=DeleteOpenIDConnectProvider?OpenIDConnectProviderArn=OpenIDConnectProviderArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes an OpenID Connect identity provider (IdP) resource object in IAM."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "08bcb2e3-1c43-4a0a-a784-ed46f2e1c44d"
            }
          ]
        }
      ]
    },
    {
      "name": "Role Instance",
      "item": [
        {
          "id": "89980269-bf6e-41ee-bc9f-b887d54c5206",
          "name": "addRoleToInstanceProfile",
          "request": {
            "url": "http://example.com/api/?Action=AddRoleToInstanceProfile?InstanceProfileName=InstanceProfileName&RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds the specified IAM role to the specified instance profile."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cf6fae47-8331-4700-8e0b-871fc01f2738"
            }
          ]
        }
      ]
    },
    {
      "name": "User Groups",
      "item": [
        {
          "id": "f135baf5-c9dc-4ab9-8662-7d00a937481d",
          "name": "addUserToGroup",
          "request": {
            "url": "http://example.com/api/?Action=AddUserToGroup?GroupName=GroupName&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds the specified user to the specified group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a28eb0d8-71b0-4852-8e04-0f541e07af7a"
            }
          ]
        }
      ]
    },
    {
      "name": "Group Policies",
      "item": [
        {
          "id": "136088a0-44f0-4772-8428-23dc13f9a96a",
          "name": "attachGroupPolicy",
          "request": {
            "url": "http://example.com/api/?Action=AttachGroupPolicy?GroupName=GroupName&PolicyArn=PolicyArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches the specified managed policy to the specified IAM group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "873af1b2-29ba-47fd-a5ff-3bc8804732c4"
            }
          ]
        },
        {
          "id": "bd4cf0ca-2917-4eb8-a282-fcf231937006",
          "name": "deleteGroupPolicy",
          "request": {
            "url": "http://example.com/api/?Action=DeleteGroupPolicy?GroupName=GroupName&PolicyName=PolicyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified inline policy that is embedded in the specified IAM\n      group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "459d029f-879a-402d-909f-7521c8961f4c"
            }
          ]
        }
      ]
    },
    {
      "name": "Role Policies",
      "item": [
        {
          "id": "67d7b88c-10d3-4a18-852d-515957e40b97",
          "name": "attachRolePolicy",
          "request": {
            "url": "http://example.com/api/?Action=AttachRolePolicy?PolicyArn=PolicyArn&RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches the specified managed policy to the specified IAM role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "190d49c3-d845-4fb6-94c4-07ad7c75142c"
            }
          ]
        },
        {
          "id": "de0470c1-865a-4712-acdb-e06ab3d77ec1",
          "name": "deleteRolePolicy",
          "request": {
            "url": "http://example.com/api/?Action=DeleteRolePolicy?PolicyName=PolicyName&RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified inline policy that is embedded in the specified IAM\n      role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5c5d5684-a203-4d89-aa7c-7fc6ca9289fa"
            }
          ]
        }
      ]
    },
    {
      "name": "User Policies",
      "item": [
        {
          "id": "a0295082-d1b1-4adb-ac89-77a32bc97993",
          "name": "attachUserPolicy",
          "request": {
            "url": "http://example.com/api/?Action=AttachUserPolicy?PolicyArn=PolicyArn&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches the specified managed policy to the specified user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a35d3de3-c3a7-47de-ac46-be683e728111"
            }
          ]
        }
      ]
    },
    {
      "name": "Passwords",
      "item": [
        {
          "id": "9c95ec07-dc51-4f73-ae14-66d5d224bffe",
          "name": "changePassword",
          "request": {
            "url": "http://example.com/api/?Action=ChangePassword?NewPassword=NewPassword&OldPassword=OldPassword",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Changes the password of the IAM user who is calling this action."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "58786156-5b20-4db7-b177-51cf4774e3f6"
            }
          ]
        }
      ]
    },
    {
      "name": "Access Keys",
      "item": [
        {
          "id": "c6097652-7bc0-466b-9cd8-3f2dacdc4336",
          "name": "createAccessKey",
          "request": {
            "url": "http://example.com/api/?Action=CreateAccessKey?UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new AWS secret access key and corresponding AWS access key ID for the\n      specified user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "410d2bc8-5541-45a6-9aa9-e30cd74804e6"
            }
          ]
        },
        {
          "id": "803ddfc9-9d50-49e7-b849-0e82f00340f3",
          "name": "deleteAccessKey",
          "request": {
            "url": "http://example.com/api/?Action=DeleteAccessKey?AccessKeyId=AccessKeyId&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the access key pair associated with the specified IAM user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1291e76e-d2ce-4a35-bcab-9105ab45767b"
            }
          ]
        }
      ]
    },
    {
      "name": "Account Alias",
      "item": [
        {
          "id": "e9a5435a-d36d-42f0-87b3-beea676523b1",
          "name": "createAccountAlias",
          "request": {
            "url": "http://example.com/api/?Action=CreateAccountAlias?AccountAlias=AccountAlias",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an alias for your AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6ace9bae-a910-41cb-9c06-ce360eab26a7"
            }
          ]
        },
        {
          "id": "7a3aec79-5e20-4852-a065-06a21687923c",
          "name": "deleteAccountAlias",
          "request": {
            "url": "http://example.com/api/?Action=DeleteAccountAlias?AccountAlias=AccountAlias",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified AWS account alias."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cf85cdde-d1f6-4a06-b0a4-d79fa7ae6567"
            }
          ]
        }
      ]
    },
    {
      "name": "Groups",
      "item": [
        {
          "id": "2e8012ed-e6f4-4ec6-be6c-3c4d266db447",
          "name": "createGroup",
          "request": {
            "url": "http://example.com/api/?Action=CreateGroup?GroupName=GroupName&Path=Path",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0359c954-a224-471a-99ff-3d8617a0ed82"
            }
          ]
        },
        {
          "id": "049dc101-a1e3-48ca-a1e1-c443f2a727cb",
          "name": "deleteGroup",
          "request": {
            "url": "http://example.com/api/?Action=DeleteGroup?GroupName=GroupName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified IAM group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "af307f60-c5f5-4d16-ba7f-122097e77cec"
            }
          ]
        }
      ]
    },
    {
      "name": "Instance Profiles",
      "item": [
        {
          "id": "4467fda7-bbe7-4935-a07c-1c9611c2124a",
          "name": "createInstanceProfile",
          "request": {
            "url": "http://example.com/api/?Action=CreateInstanceProfile?InstanceProfileName=InstanceProfileName&Path=Path",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new instance profile."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8f289830-7423-4d00-b527-70b23f4e2d68"
            }
          ]
        },
        {
          "id": "94044705-d7bf-420a-aabd-6ba12bf13403",
          "name": "deleteInstanceProfile",
          "request": {
            "url": "http://example.com/api/?Action=DeleteInstanceProfile?InstanceProfileName=InstanceProfileName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified instance profile."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "af99a393-d50f-46c8-a1bd-962b6335f492"
            }
          ]
        }
      ]
    },
    {
      "name": "Login Profiles",
      "item": [
        {
          "id": "206fd1dc-6efe-4622-91e7-5db7817e5abd",
          "name": "createLoginProfile",
          "request": {
            "url": "http://example.com/api/?Action=CreateLoginProfile?Password=Password&PasswordResetRequired=PasswordResetRequired&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a password for the specified user, giving the user the ability to access AWS\n      services through the AWS Management Console."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "019a8a10-93d8-4b7a-8b4b-f2ad7b227560"
            }
          ]
        },
        {
          "id": "80726430-fea8-4404-a572-640a8ec251ad",
          "name": "deleteLoginProfile",
          "request": {
            "url": "http://example.com/api/?Action=DeleteLoginProfile?UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the password for the specified IAM user, which terminates the user's ability\n      to access AWS services through the AWS Management Console."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "429d571c-2e77-4299-a204-f67e4e1152bf"
            }
          ]
        }
      ]
    },
    {
      "name": "Policies",
      "item": [
        {
          "id": "d64a13b5-5a12-4b7e-9548-9fe014a0126a",
          "name": "createPolicy",
          "request": {
            "url": "http://example.com/api/?Action=CreatePolicy?Description=Description&Path=Path&PolicyDocument=PolicyDocument&PolicyName=PolicyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new managed policy for your AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "68b46646-5019-4033-8367-4d43c0104eab"
            }
          ]
        },
        {
          "id": "0c327e54-5fd2-411b-a87f-a105ca5ff848",
          "name": "createPolicyVersion",
          "request": {
            "url": "http://example.com/api/?Action=CreatePolicyVersion?PolicyArn=PolicyArn&PolicyDocument=PolicyDocument&SetAsDefault=SetAsDefault",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new version of the specified managed policy."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3a025432-681e-45f1-9d9a-2603b4db5cb0"
            }
          ]
        },
        {
          "id": "64c09a9a-6afd-489d-ad8b-66ff78cd208c",
          "name": "deletePolicy",
          "request": {
            "url": "http://example.com/api/?Action=DeletePolicy?PolicyArn=PolicyArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified managed policy."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f4b2f4a1-17e5-4589-baad-3548aefe1adb"
            }
          ]
        },
        {
          "id": "7edf96d9-f834-419d-9031-ab717938fce3",
          "name": "deletePolicyVersion",
          "request": {
            "url": "http://example.com/api/?Action=DeletePolicyVersion?PolicyArn=PolicyArn&VersionId=VersionId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified version from the specified managed policy."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "43dcbd71-cd5a-4d33-840f-453b892e5367"
            }
          ]
        }
      ]
    },
    {
      "name": "Roles",
      "item": [
        {
          "id": "e0859049-ead8-4dde-9668-c45907de9d5a",
          "name": "createRole",
          "request": {
            "url": "http://example.com/api/?Action=CreateRole?AssumeRolePolicyDocument=AssumeRolePolicyDocument&Path=Path&RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new role for your AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bc19cc41-f9c3-4bdf-b1d0-052a529a2a92"
            }
          ]
        },
        {
          "id": "5df80574-45b0-4259-8595-df3b5fb97b3f",
          "name": "deleteRole",
          "request": {
            "url": "http://example.com/api/?Action=DeleteRole?RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1998ced2-48c7-417f-8330-4a19150439b5"
            }
          ]
        }
      ]
    },
    {
      "name": "SAML Providers",
      "item": [
        {
          "id": "6911689e-eb0a-4644-8810-f26f6176abd8",
          "name": "createSAMLProvider",
          "request": {
            "url": "http://example.com/api/?Action=CreateSAMLProvider?Name=Name&SAMLMetadataDocument=SAMLMetadataDocument",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an IAM resource that describes an identity provider (IdP) that supports SAML\n      2."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "86997d7f-4e73-407b-add9-15ddcd5b9abf"
            }
          ]
        },
        {
          "id": "704451ec-352c-4035-b608-1f4c0457c30d",
          "name": "deleteSAMLProvider",
          "request": {
            "url": "http://example.com/api/?Action=DeleteSAMLProvider?SAMLProviderArn=SAMLProviderArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a SAML provider resource in IAM."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "38900826-83f5-4978-8b9c-d1d8114f6d0f"
            }
          ]
        }
      ]
    },
    {
      "name": "Service Specific Credentials",
      "item": [
        {
          "id": "13c8babc-55f9-48e6-9fd3-b59147c2560b",
          "name": "createServiceSpecificCredential",
          "request": {
            "url": "http://example.com/api/?Action=CreateServiceSpecificCredential?ServiceName=ServiceName&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Generates a set of credentials consisting of a user name and password that can be used\n      to access the service specified in the request."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2e27704f-987c-459f-a0ad-5fe1d3ec4878"
            }
          ]
        },
        {
          "id": "82fdb1c0-0769-45b3-9cc5-b2fb50a9e8db",
          "name": "deleteServiceSpecificCredential",
          "request": {
            "url": "http://example.com/api/?Action=DeleteServiceSpecificCredential?ServiceSpecificCredentialId=ServiceSpecificCredentialId&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified service-specific credential."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "657bccf5-6f98-43a1-a010-cf7b328673a5"
            }
          ]
        }
      ]
    },
    {
      "name": "Users",
      "item": [
        {
          "id": "2ee3bcc7-bff5-4f76-8e6b-f31c083d938c",
          "name": "createUser",
          "request": {
            "url": "http://example.com/api/?Action=CreateUser?Path=Path&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new IAM user for your AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b41bff8e-dc6c-4c7a-a8f1-b4a7f77f602a"
            }
          ]
        }
      ]
    },
    {
      "name": "Virtual MFA Device",
      "item": [
        {
          "id": "934f1b07-bb4b-4c66-a76a-abe0fd28d27b",
          "name": "createVirtualMFADevice",
          "request": {
            "url": "http://example.com/api/?Action=CreateVirtualMFADevice?Path=Path&VirtualMFADeviceName=VirtualMFADeviceName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new virtual MFA device for the AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "85a2998c-86f7-4e83-bdbf-98ea87d8efd9"
            }
          ]
        },
        {
          "id": "643df1b8-20d7-4b97-97c7-32f2ff489783",
          "name": "deactivateMFADevice",
          "request": {
            "url": "http://example.com/api/?Action=DeactivateMFADevice?SerialNumber=SerialNumber&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deactivates the specified MFA device and removes it from association with the user name\n      for which it was originally enabled."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ae8f27ec-9c57-4552-bfaf-bc696a07d195"
            }
          ]
        }
      ]
    },
    {
      "name": "Account Password Policies",
      "item": [
        {
          "id": "98b68d15-ac08-4582-af90-7ef18f97dc9a",
          "name": "deleteAccountPasswordPolicy",
          "request": {
            "url": "http://example.com/api/?Action=DeleteAccountPasswordPolicy?LimitExceeded=LimitExceeded&NoSuchEntity=NoSuchEntity&ServiceFailure=ServiceFailure",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the password policy for the AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "80f6dddd-c081-44ff-9441-14a012ea6b64"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Certificates",
      "item": [
        {
          "id": "bafb96ef-073d-49d2-8c3f-e3a961078de1",
          "name": "deleteServerCertificate",
          "request": {
            "url": "http://example.com/api/?Action=DeleteServerCertificate?ServerCertificateName=ServerCertificateName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified server certificate."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a1087914-0506-420b-95db-c205277324ca"
            }
          ]
        }
      ]
    }
  ]
}