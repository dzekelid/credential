{
  "info": {
    "name": "AWS Identity and Access Management API Reset Service Specific Credential",
    "_postman_id": "027a1143-64ee-4f89-8722-0fab58afca3b",
    "description": "Resets the password for a service-specific credential.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "OpenID Connect Providers",
      "item": [
        {
          "id": "a0cc0b6e-b777-4c4f-84cb-dc79f0945835",
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
              "id": "8a9270c8-38a5-43a9-958d-e51d96eb3dbe"
            }
          ]
        },
        {
          "id": "08b6e26c-863c-4222-90f1-b4ce81f46f2d",
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
              "id": "7255b127-fa10-4fe0-9875-1261d30f854f"
            }
          ]
        },
        {
          "id": "e1d40456-168f-4bb9-ae6b-980ad5904ee6",
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
              "id": "7fcbb17b-3f04-4d2e-aedd-6d9147291be6"
            }
          ]
        },
        {
          "id": "c1a2bc36-5415-4f52-b4e0-b818ce842529",
          "name": "getOpenIDConnectProvider",
          "request": {
            "url": "http://example.com/api/?Action=GetOpenIDConnectProvider?OpenIDConnectProviderArn=OpenIDConnectProviderArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns information about the specified OpenID Connect (OIDC) provider resource object\n      in IAM."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6323b076-3077-47d4-882a-2368b3c79a59"
            }
          ]
        },
        {
          "id": "c71d37b1-2367-40c7-a3fa-3e870f531d26",
          "name": "listOpenIDConnectProviders",
          "request": {
            "url": "http://example.com/api/?Action=ListOpenIDConnectProviders?OpenIDConnectProviderList.member.N=OpenIDConnectProviderList.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists information about the IAM OpenID Connect (OIDC) provider resource objects\n      defined in the AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3b612c90-fd06-4791-8181-cfb21ecb0a6b"
            }
          ]
        },
        {
          "id": "c276c46d-5c05-4a2b-ac02-24f1a99019eb",
          "name": "removeClientIDFromOpenIDConnectProvider",
          "request": {
            "url": "http://example.com/api/?Action=RemoveClientIDFromOpenIDConnectProvider?ClientID=ClientID&OpenIDConnectProviderArn=OpenIDConnectProviderArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Removes the specified client ID (also known as audience) from the list of client IDs\n      registered for the specified IAM OpenID Connect (OIDC) provider resource object."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2a90d831-d549-4b6a-b64e-087974a8e681"
            }
          ]
        }
      ]
    },
    {
      "name": "Role Instance",
      "item": [
        {
          "id": "f37e35bc-b2a3-48eb-92e7-83351042c7ba",
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
              "id": "b77eb3c4-09cc-43db-a68f-b5a088246740"
            }
          ]
        }
      ]
    },
    {
      "name": "User Groups",
      "item": [
        {
          "id": "750048e9-c385-4454-a928-88bcb38ae4da",
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
              "id": "23500ef2-9c7c-4007-be98-5804e13690e5"
            }
          ]
        }
      ]
    },
    {
      "name": "Group Policies",
      "item": [
        {
          "id": "ad04dad8-4cc3-4a5b-a69d-84c62ab3fe30",
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
              "id": "38f9dfed-9c03-42a6-8fee-1229bd903e35"
            }
          ]
        },
        {
          "id": "3943229d-fb11-41ce-8be7-3194ebef1582",
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
              "id": "6d11f590-b0e6-410a-b2c9-6df5804dfc11"
            }
          ]
        },
        {
          "id": "40025c03-f5ee-4634-a442-881d14fa415d",
          "name": "detachGroupPolicy",
          "request": {
            "url": "http://example.com/api/?Action=DetachGroupPolicy?GroupName=GroupName&PolicyArn=PolicyArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Removes the specified managed policy from the specified IAM group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7407e170-5d97-49f9-9a72-86609c516044"
            }
          ]
        },
        {
          "id": "876a21cf-f869-4d35-b9a8-d1b32d1e25d0",
          "name": "getGroupPolicy",
          "request": {
            "url": "http://example.com/api/?Action=GetGroupPolicy?GroupName=GroupName&PolicyName=PolicyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the specified inline policy document that is embedded in the specified IAM\n      group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f979a853-6afc-429d-aea1-2eac0951e109"
            }
          ]
        },
        {
          "id": "2603b642-af1a-4f13-af45-479abd0540b4",
          "name": "listGroupPolicies",
          "request": {
            "url": "http://example.com/api/?Action=ListGroupPolicies?GroupName=GroupName&Marker=Marker&MaxItems=MaxItems",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the names of the inline policies that are embedded in the specified IAM\n      group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1241252e-5a06-434e-9a2b-ac93b96d8651"
            }
          ]
        },
        {
          "id": "9ff80ff5-7001-4f57-9431-91b18bd95fca",
          "name": "putGroupPolicy",
          "request": {
            "url": "http://example.com/api/?Action=PutGroupPolicy?GroupName=GroupName&PolicyDocument=PolicyDocument&PolicyName=PolicyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds or updates an inline policy document that is embedded in the specified IAM\n      group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "af0cfe96-59c1-4f65-bd8a-b3e762b330d0"
            }
          ]
        }
      ]
    },
    {
      "name": "Role Policies",
      "item": [
        {
          "id": "8b4844f2-9244-46fc-a1c4-2936ba7002e5",
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
              "id": "2718ba19-f366-4dae-8e62-988232da6a49"
            }
          ]
        },
        {
          "id": "72e9adad-b0e7-48c9-9e06-57faa1c592c4",
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
              "id": "1623fdf5-0887-44fa-a299-62bb75068b58"
            }
          ]
        },
        {
          "id": "54f4809e-cd5a-4020-a916-ef45f40caff8",
          "name": "detachRolePolicy",
          "request": {
            "url": "http://example.com/api/?Action=DetachRolePolicy?PolicyArn=PolicyArn&RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Removes the specified managed policy from the specified role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bd1002fb-7a9d-4740-96b3-34bd4fec974c"
            }
          ]
        },
        {
          "id": "045f417b-fdf7-4734-bcf7-f4ed8e5d93e5",
          "name": "getRolePolicy",
          "request": {
            "url": "http://example.com/api/?Action=GetRolePolicy?PolicyName=PolicyName&RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the specified inline policy document that is embedded with the specified\n      IAM role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9fcd3e0c-02ee-414f-a8a6-c106ee56b034"
            }
          ]
        },
        {
          "id": "bd5007f9-02de-4b9a-bee0-876e20ef63ce",
          "name": "listRolePolicies",
          "request": {
            "url": "http://example.com/api/?Action=ListRolePolicies?Marker=Marker&MaxItems=MaxItems&RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the names of the inline policies that are embedded in the specified IAM\n      role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "453113ca-991b-4336-a7a5-167e8e75c4b0"
            }
          ]
        },
        {
          "id": "ce2db7f9-3ceb-4916-b78c-47b0edca9bc5",
          "name": "putRolePolicy",
          "request": {
            "url": "http://example.com/api/?Action=PutRolePolicy?PolicyDocument=PolicyDocument&PolicyName=PolicyName&RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds or updates an inline policy document that is embedded in the specified IAM\n      role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cd672d49-de33-4644-8d46-bdf70c295dd6"
            }
          ]
        }
      ]
    },
    {
      "name": "User Policies",
      "item": [
        {
          "id": "653ca4f3-2aff-42ef-813f-9717cdff5e6b",
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
              "id": "87784883-9316-4599-bd9d-a3075a13e792"
            }
          ]
        },
        {
          "id": "9eea1d22-667c-4057-be51-eb7759fbfca0",
          "name": "deleteUserPolicy",
          "request": {
            "url": "http://example.com/api/?Action=DeleteUserPolicy?PolicyName=PolicyName&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified inline policy that is embedded in the specified IAM\n      user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "afb1b4aa-1477-48f6-8191-01fc443bc098"
            }
          ]
        },
        {
          "id": "95c6047f-2f4b-4dcd-a618-dca4fa830fb7",
          "name": "detachUserPolicy",
          "request": {
            "url": "http://example.com/api/?Action=DetachUserPolicy?PolicyArn=PolicyArn&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Removes the specified managed policy from the specified user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ad0d0786-c6a8-49d2-9aa1-674193f3fa2a"
            }
          ]
        },
        {
          "id": "4b9c4cb7-6082-4e6e-a7d7-246adafbec7b",
          "name": "getUserPolicy",
          "request": {
            "url": "http://example.com/api/?Action=GetUserPolicy?PolicyName=PolicyName&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the specified inline policy document that is embedded in the specified IAM\n      user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a36be06a-b17a-4559-91f6-77cd32f3ed31"
            }
          ]
        },
        {
          "id": "0f4f6eab-14f3-4fac-9c77-dd9376238a54",
          "name": "listUserPolicies",
          "request": {
            "url": "http://example.com/api/?Action=ListUserPolicies?Marker=Marker&MaxItems=MaxItems&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the names of the inline policies embedded in the specified IAM user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9a25f72b-43fa-45a3-b701-d061abfa9b2c"
            }
          ]
        }
      ]
    },
    {
      "name": "Passwords",
      "item": [
        {
          "id": "777e5840-8268-414e-8e39-a8aefe625b0f",
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
              "id": "eb5231af-4220-4ed6-93f2-6275dcadf3d6"
            }
          ]
        }
      ]
    },
    {
      "name": "Access Keys",
      "item": [
        {
          "id": "30f833bd-c48d-4a0e-ab29-290f99e4806a",
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
              "id": "18d4e6f6-e25f-41b3-b039-ef13ce02fef2"
            }
          ]
        },
        {
          "id": "f27b44d5-b671-4f16-aa0c-cff476bfc2a4",
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
              "id": "af7c9ea7-4766-44a9-b1a5-83345aafe0d1"
            }
          ]
        },
        {
          "id": "28c08a64-2017-4988-ad65-589de0ecacc5",
          "name": "getAccessKeyLastUsed",
          "request": {
            "url": "http://example.com/api/?Action=GetAccessKeyLastUsed?AccessKeyId=AccessKeyId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about when the specified access key was last used."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "93dac792-74a8-4417-b8a9-71099310eba8"
            }
          ]
        },
        {
          "id": "be00a5e8-8c55-4d68-95d0-ba2206c08fa3",
          "name": "listAccessKeys",
          "request": {
            "url": "http://example.com/api/?Action=ListAccessKeys?Marker=Marker&MaxItems=MaxItems&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns information about the access key IDs associated with the specified IAM user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "89c934b5-c864-4ecd-8ed6-a81f87cbaebf"
            }
          ]
        }
      ]
    },
    {
      "name": "Account Alias",
      "item": [
        {
          "id": "88ea8c4d-48ff-4c97-82aa-cd617ffbdd79",
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
              "id": "1dbdddca-08ca-4ff2-8067-c474193d4657"
            }
          ]
        },
        {
          "id": "9599c61f-216d-48b6-95d8-589f4354c1cd",
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
              "id": "c75ee426-d0aa-4779-b134-e9195b9d4176"
            }
          ]
        }
      ]
    },
    {
      "name": "Groups",
      "item": [
        {
          "id": "fe88db3e-19d9-40a2-aefb-349172b6757f",
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
              "id": "b59d62d2-d973-440c-9d3e-45f02d90b12d"
            }
          ]
        },
        {
          "id": "0883bfd8-a8ff-4eb3-814e-e8f170ca23e0",
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
              "id": "3d2358d9-c211-4cc2-8d95-a0138bbec9c9"
            }
          ]
        },
        {
          "id": "cd44ef98-c51b-4a52-a207-0079d5384031",
          "name": "getGroup",
          "request": {
            "url": "http://example.com/api/?Action=GetGroup?GroupName=GroupName&Marker=Marker&MaxItems=MaxItems",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of IAM users that are in the specified IAM group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "57fe8902-7909-41f7-81fd-b4b3808aef35"
            }
          ]
        },
        {
          "id": "2820933d-dbbe-4473-a89a-56517c9fa900",
          "name": "listGroups",
          "request": {
            "url": "http://example.com/api/?Action=ListGroups?Marker=Marker&MaxItems=MaxItems&PathPrefix=PathPrefix",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the IAM groups that have the specified path prefix."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b4f1a524-dc66-4696-898f-0021e56ee1c7"
            }
          ]
        }
      ]
    },
    {
      "name": "Instance Profiles",
      "item": [
        {
          "id": "ba9d9e00-99b0-4e79-b62d-2539902a5805",
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
              "id": "63af9280-9296-44e8-9d40-76c1db117d57"
            }
          ]
        },
        {
          "id": "524a4910-1668-40cd-9ab3-bb7f7e77aa5e",
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
              "id": "f0643860-c9b4-4821-997c-ee4a743fa7b3"
            }
          ]
        },
        {
          "id": "49f71056-0a33-4422-962d-9e234088715c",
          "name": "getInstanceProfile",
          "request": {
            "url": "http://example.com/api/?Action=GetInstanceProfile?InstanceProfileName=InstanceProfileName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about the specified instance profile, including the instance\n      profile's path, GUID, ARN, and role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "927ab9aa-01ba-4ee3-a802-de97015c7080"
            }
          ]
        },
        {
          "id": "0a29e785-b658-477f-af02-d1584a94b72e",
          "name": "listInstanceProfiles",
          "request": {
            "url": "http://example.com/api/?Action=ListInstanceProfiles?Marker=Marker&MaxItems=MaxItems&PathPrefix=PathPrefix",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the instance profiles that have the specified path prefix."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9e424935-4a2b-4243-9329-7cf8df73563e"
            }
          ]
        }
      ]
    },
    {
      "name": "Login Profiles",
      "item": [
        {
          "id": "c0e447e4-4abf-4937-a10d-a09292de19be",
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
              "id": "7eb0bc3e-6fac-4190-8e67-a5d520774631"
            }
          ]
        },
        {
          "id": "8289bb93-c2cc-42ab-ac3b-6aa401329724",
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
              "id": "f9b86b73-a828-400f-bc6f-83514734b832"
            }
          ]
        },
        {
          "id": "9d8eb41c-6644-478e-9351-176d4fd1b589",
          "name": "getLoginProfile",
          "request": {
            "url": "http://example.com/api/?Action=GetLoginProfile?UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the user name and password-creation date for the specified IAM user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e6af39f0-0143-4ed1-80e1-443065f858fd"
            }
          ]
        }
      ]
    },
    {
      "name": "Policies",
      "item": [
        {
          "id": "343f57a1-67b4-4074-af5e-ff313ea94d44",
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
              "id": "566a5402-1f73-42f8-9100-edabc39ec0d1"
            }
          ]
        },
        {
          "id": "d91bba61-730a-40ec-a2ae-d65c3fc81dbb",
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
              "id": "f3e9e83c-3e8f-4e59-8825-aa2954016edf"
            }
          ]
        },
        {
          "id": "9916ff39-5fe5-4e3c-819f-c0e086df4347",
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
              "id": "b2b912c4-2c73-4b62-8d9e-9a71d92d32df"
            }
          ]
        },
        {
          "id": "758e1ce6-80b4-4471-8913-e365bb488d30",
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
              "id": "a7cd61d2-a852-4c0d-ae1d-aa8247014bbc"
            }
          ]
        },
        {
          "id": "36d74e4d-9f57-4254-a905-3e9ae0d2ca1b",
          "name": "getPolicy",
          "request": {
            "url": "http://example.com/api/?Action=GetPolicy?PolicyArn=PolicyArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about the specified managed policy, including the policy's\n      default version and the total number of IAM users, groups, and roles to which the policy is\n      attached."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "91646de5-78cc-4583-b3bf-52261b4898f4"
            }
          ]
        },
        {
          "id": "dc18f175-1645-4fcd-a626-5b88c9965b10",
          "name": "getPolicyVersion",
          "request": {
            "url": "http://example.com/api/?Action=GetPolicyVersion?PolicyArn=PolicyArn&VersionId=VersionId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about the specified version of the specified managed policy,\n      including the policy document."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1d2f1907-4360-4b0d-97d6-a8daeb0a0e56"
            }
          ]
        }
      ]
    },
    {
      "name": "Roles",
      "item": [
        {
          "id": "2f68aac5-7f38-419e-8a93-1f6c62a9d1d3",
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
              "id": "f54267ab-d34f-4034-84c5-de89a6888e66"
            }
          ]
        },
        {
          "id": "522f38dd-a323-4144-a8b2-c3fbb215a94d",
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
              "id": "64772856-fc27-4e39-99e5-bf28496acb13"
            }
          ]
        },
        {
          "id": "0ed9f7d0-4bbd-4c9f-b471-9aa3b4283ce3",
          "name": "getRole",
          "request": {
            "url": "http://example.com/api/?Action=GetRole?RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about the specified role, including the role's path, GUID, ARN,\n      and the role's trust policy that grants permission to assume the role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3c7cbe86-5922-4bc4-9c1b-a62ff238f090"
            }
          ]
        },
        {
          "id": "5f61d711-51d3-4641-83fb-f82f2f826a04",
          "name": "listRoles",
          "request": {
            "url": "http://example.com/api/?Action=ListRoles?Marker=Marker&MaxItems=MaxItems&PathPrefix=PathPrefix",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the IAM roles that have the specified path prefix."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4033b6f5-9a84-4fa8-ae06-5d7abd328c88"
            }
          ]
        }
      ]
    },
    {
      "name": "SAML Providers",
      "item": [
        {
          "id": "e5e2a6c0-d76b-4505-9154-97761f319955",
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
              "id": "bb04a650-ed07-400a-a74c-ef20b23b1945"
            }
          ]
        },
        {
          "id": "ef9b1080-dbbf-4570-9886-9950c8bbe854",
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
              "id": "c5fee32b-66e5-4763-a6e7-d12ac015d4a0"
            }
          ]
        },
        {
          "id": "8a986d86-357b-43fa-81b8-6f7a34568db3",
          "name": "getSAMLProvider",
          "request": {
            "url": "http://example.com/api/?Action=GetSAMLProvider?SAMLProviderArn=SAMLProviderArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the SAML provider metadocument that was uploaded when the IAM SAML provider\n      resource object was created or updated."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "48420bf9-8bfd-484d-b657-66257d25bf8e"
            }
          ]
        },
        {
          "id": "8e2cbd9e-f3d3-484d-bbcb-0a310de98ce9",
          "name": "listSAMLProviders",
          "request": {
            "url": "http://example.com/api/?Action=ListSAMLProviders?SAMLProviderList.member.N=SAMLProviderList.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the SAML provider resource objects defined in IAM in the account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8f8b987f-afd9-4bc0-8460-6d3350656833"
            }
          ]
        }
      ]
    },
    {
      "name": "Service Specific Credentials",
      "item": [
        {
          "id": "60bfb1fe-b1cf-40d1-9764-160c450b0277",
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
              "id": "e0d8e55a-889d-4fe9-85e2-b530d9af5f37"
            }
          ]
        },
        {
          "id": "cdaffb21-b734-4ccb-b98a-9f7927e8d1d5",
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
              "id": "060c062b-f2de-4151-9f2b-27de307ebeb1"
            }
          ]
        },
        {
          "id": "d8cf31e4-6565-47de-ae54-f77974a8d087",
          "name": "listServiceSpecificCredentials",
          "request": {
            "url": "http://example.com/api/?Action=ListServiceSpecificCredentials?ServiceName=ServiceName&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns information about the service-specific credentials associated with the\n      specified IAM user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c8756199-d640-4de1-991b-70302d097005"
            }
          ]
        },
        {
          "id": "4670d58b-687e-4f45-8008-41719b563825",
          "name": "resetServiceSpecificCredential",
          "request": {
            "url": "http://example.com/api/?Action=ResetServiceSpecificCredential?ServiceSpecificCredentialId=ServiceSpecificCredentialId&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Resets the password for a service-specific credential."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2b201d78-eedc-4d71-9592-3350b7fe71ce"
            }
          ]
        }
      ]
    },
    {
      "name": "Users",
      "item": [
        {
          "id": "fbae5553-bbc2-4320-92e2-a9b57363a9a0",
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
              "id": "eaa842b0-84d0-43de-a4cb-f63dd3979536"
            }
          ]
        },
        {
          "id": "394b6e2c-0af6-4d96-8937-08577fb8886a",
          "name": "deleteUser",
          "request": {
            "url": "http://example.com/api/?Action=DeleteUser?UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified IAM user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "733ddcb7-e192-4a70-b828-fa7c599e6cf4"
            }
          ]
        },
        {
          "id": "e809c0d7-5360-4cdc-85a4-52d530f03a5b",
          "name": "getUser",
          "request": {
            "url": "http://example.com/api/?Action=GetUser?UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about the specified IAM user, including the user's creation\n      date, path, unique ID, and ARN."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "06b83c85-1d12-44d4-8d56-d7fd7c599ecf"
            }
          ]
        },
        {
          "id": "f2c1a632-218a-473b-8f92-4860ec8db40a",
          "name": "listUsers",
          "request": {
            "url": "http://example.com/api/?Action=ListUsers?Marker=Marker&MaxItems=MaxItems&PathPrefix=PathPrefix",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the IAM users that have the specified path prefix."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "66b94afe-9d46-48a0-905a-07cc030e650c"
            }
          ]
        }
      ]
    },
    {
      "name": "Virtual MFA Device",
      "item": [
        {
          "id": "017438cb-5215-45de-9cad-69b2ba657ea3",
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
              "id": "81e85946-309a-4fe8-b9d7-4f7753075868"
            }
          ]
        },
        {
          "id": "aa0ec31b-fe80-466e-9117-670fa4b498bf",
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
              "id": "48d5d004-1bf2-4f8f-8d77-7ffe9c6f24f0"
            }
          ]
        }
      ]
    },
    {
      "name": "Account Password Policies",
      "item": [
        {
          "id": "adaf1485-f448-437e-93c1-7d5e38aeeb4a",
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
              "id": "2c9e3f5a-08c8-4202-b8d2-d8356aba0b9d"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Certificates",
      "item": [
        {
          "id": "b6d0a0b0-b6a7-41a2-9925-b01a653161b3",
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
              "id": "525eddf2-339d-4281-a5f4-6e984287caa8"
            }
          ]
        },
        {
          "id": "c22b995c-026c-4dc3-a8c1-5556bba334bb",
          "name": "getServerCertificate",
          "request": {
            "url": "http://example.com/api/?Action=GetServerCertificate?ServerCertificateName=ServerCertificateName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about the specified server certificate stored in IAM."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2597779b-8f38-4be8-a064-8df218ec2c52"
            }
          ]
        }
      ]
    },
    {
      "name": "Signing Certificates",
      "item": [
        {
          "id": "c6aa0db5-02d7-48b8-bef9-afa0a37fd709",
          "name": "deleteSigningCertificate",
          "request": {
            "url": "http://example.com/api/?Action=DeleteSigningCertificate?CertificateId=CertificateId&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a signing certificate associated with the specified IAM user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "79f602a0-8571-431a-96fe-ed25b3aa43ac"
            }
          ]
        },
        {
          "id": "ed3f1b78-63f3-4423-aa7f-1cff4c5a44a9",
          "name": "listSigningCertificates",
          "request": {
            "url": "http://example.com/api/?Action=ListSigningCertificates?Marker=Marker&MaxItems=MaxItems&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns information about the signing certificates associated with the specified IAM\n      user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "97dd8c29-ff7d-4ad7-907f-0b0facfcaa99"
            }
          ]
        }
      ]
    },
    {
      "name": "SSH Public Key",
      "item": [
        {
          "id": "25a54d61-d86c-4bca-84b2-5744fa285c64",
          "name": "deleteSSHPublicKey",
          "request": {
            "url": "http://example.com/api/?Action=DeleteSSHPublicKey?SSHPublicKeyId=SSHPublicKeyId&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified SSH public key."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f02206f3-5200-4dd3-8537-e22f98e81677"
            }
          ]
        },
        {
          "id": "a5a89949-40df-4987-8084-c8a0456bba66",
          "name": "getSSHPublicKey",
          "request": {
            "url": "http://example.com/api/?Action=GetSSHPublicKey?Encoding=Encoding&SSHPublicKeyId=SSHPublicKeyId&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the specified SSH public key, including metadata about the key."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a092efc1-6e6d-4267-9770-16a3a34a1f0d"
            }
          ]
        }
      ]
    },
    {
      "name": "Virtual MFA Devices",
      "item": [
        {
          "id": "18d4f156-5d22-4689-b304-7a932a99eb4c",
          "name": "deleteVirtualMFADevice",
          "request": {
            "url": "http://example.com/api/?Action=DeleteVirtualMFADevice?SerialNumber=SerialNumber",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a virtual MFA device."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cb9f463c-ef34-4a4e-803f-f2649e60a76d"
            }
          ]
        },
        {
          "id": "ba9748e4-a496-49ab-8db2-9c038a6d427f",
          "name": "listVirtualMFADevices",
          "request": {
            "url": "http://example.com/api/?Action=ListVirtualMFADevices?AssignmentStatus=AssignmentStatus&Marker=Marker&MaxItems=MaxItems",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the virtual MFA devices defined in the AWS account by assignment status."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "41e719cf-687c-456b-8c77-bc6160d2ee63"
            }
          ]
        }
      ]
    },
    {
      "name": "MFA Devices",
      "item": [
        {
          "id": "32db0992-8c2c-4c4a-9f78-dd00084bac6c",
          "name": "enableMFADevice",
          "request": {
            "url": "http://example.com/api/?Action=EnableMFADevice?AuthenticationCode1=AuthenticationCode1&AuthenticationCode2=AuthenticationCode2&SerialNumber=SerialNumber&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Enables the specified MFA device and associates it with the specified IAM user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1118acde-bc99-4217-af6c-c8d6d100913f"
            }
          ]
        },
        {
          "id": "68915c9b-b8de-4a6d-9cb8-a7ef458ccb62",
          "name": "listMFADevices",
          "request": {
            "url": "http://example.com/api/?Action=ListMFADevices?Marker=Marker&MaxItems=MaxItems&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the MFA devices for an IAM user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c461a08a-1624-43fc-af68-2608b6053ae2"
            }
          ]
        }
      ]
    },
    {
      "name": "Credential Reports",
      "item": [
        {
          "id": "506b6bcb-6c65-4628-bc88-16b8b24be234",
          "name": "generateCredentialReport",
          "request": {
            "url": "http://example.com/api/?Action=GenerateCredentialReport?Description=Description&State=State",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Generates a credential report for the AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "808f2be9-c42c-43be-8e2a-71447e0506b8"
            }
          ]
        },
        {
          "id": "4ec0141b-c939-4683-a589-5bf08436b408",
          "name": "getCredentialReport",
          "request": {
            "url": "http://example.com/api/?Action=GetCredentialReport?Content=Content&GeneratedTime=GeneratedTime&ReportFormat=ReportFormat",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves a credential report for the AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "37ea1e86-cf81-42e0-834b-e51367d77ea8"
            }
          ]
        }
      ]
    },
    {
      "name": "Accounts",
      "item": [
        {
          "id": "7f8c158e-c3db-4fd3-902f-abfa4d6e6b28",
          "name": "getAccountAuthorizationDetails",
          "request": {
            "url": "http://example.com/api/?Action=GetAccountAuthorizationDetails?Filter.member.N=Filter.member.N&Marker=Marker&MaxItems=MaxItems",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about all IAM users, groups, roles, and policies in your AWS\n      account, including their relationships to one another."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9ee0c791-5904-45e3-974d-cad2489ffe2f"
            }
          ]
        },
        {
          "id": "0d2373f0-79ae-4982-9cb2-02f56e663dbe",
          "name": "getAccountPasswordPolicy",
          "request": {
            "url": "http://example.com/api/?Action=GetAccountPasswordPolicy?PasswordPolicy=PasswordPolicy",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the password policy for the AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5b4a01b5-b35c-43a5-a37e-767cda32d99e"
            }
          ]
        },
        {
          "id": "8c7803d7-b465-4e90-9127-7243516256e9",
          "name": "getAccountSummary",
          "request": {
            "url": "http://example.com/api/?Action=GetAccountSummary?SummaryMap\n            , SummaryMap.entry.N.key (key), SummaryMapentry.N.value (value)=SummaryMap%0A%20%20%20%20%20%20%20%20%20%20%20%20%2C%20SummaryMap.entry.N.key%20%28key%29%2C%20SummaryMapentry.N.value%20%28value%29",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about IAM entity usage and IAM quotas in the AWS\n      account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "707b690c-115a-4d1c-b8cf-e08adbcbbb35"
            }
          ]
        }
      ]
    },
    {
      "name": "Context Keys For Custom Policies",
      "item": [
        {
          "id": "d6455b46-7bc8-491a-a435-535c228d6be5",
          "name": "getContextKeysForCustomPolicy",
          "request": {
            "url": "http://example.com/api/?Action=GetContextKeysForCustomPolicy?PolicyInputList.member.N=PolicyInputList.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets a list of all of the context keys referenced in the input policies."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f78aeab7-8698-4f54-a88e-c28db9340107"
            }
          ]
        }
      ]
    },
    {
      "name": "Context Keys For Principal Policies",
      "item": [
        {
          "id": "522de4c2-bd6e-4af2-8dd1-39d36579f073",
          "name": "getContextKeysForPrincipalPolicy",
          "request": {
            "url": "http://example.com/api/?Action=GetContextKeysForPrincipalPolicy?PolicyInputList.member.N=PolicyInputList.member.N&PolicySourceArn=PolicySourceArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets a list of all of the context keys referenced in all of the IAM policies attached\n      to the specified IAM entity."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3c7193e0-66e2-4fd7-8c28-a907fc62cd4b"
            }
          ]
        }
      ]
    },
    {
      "name": "Account Aliases",
      "item": [
        {
          "id": "f5f97f1a-7019-4d1c-bde7-151336dd3510",
          "name": "listAccountAliases",
          "request": {
            "url": "http://example.com/api/?Action=ListAccountAliases?Marker=Marker&MaxItems=MaxItems",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the account alias associated with the AWS account (Note: you can have only\n      one)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e5629ba7-f04d-49da-9dff-c34cbd66513a"
            }
          ]
        }
      ]
    },
    {
      "name": "Attached Group Policies",
      "item": [
        {
          "id": "ed0031f1-c5ab-4b84-9870-a95e27f17cec",
          "name": "listAttachedGroupPolicies",
          "request": {
            "url": "http://example.com/api/?Action=ListAttachedGroupPolicies?GroupName=GroupName&Marker=Marker&MaxItems=MaxItems&PathPrefix=PathPrefix",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists all managed policies that are attached to the specified IAM group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6fadfc75-d2f2-4017-9412-41a561374c85"
            }
          ]
        }
      ]
    },
    {
      "name": "Attached Role Policies",
      "item": [
        {
          "id": "bef71085-0262-4edb-bc4f-b4cb77f8fcd2",
          "name": "listAttachedRolePolicies",
          "request": {
            "url": "http://example.com/api/?Action=ListAttachedRolePolicies?Marker=Marker&MaxItems=MaxItems&PathPrefix=PathPrefix&RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists all managed policies that are attached to the specified IAM role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "670fb5