---

copyright:
  years: 2017, 2018
lastupdated: "2018-03-16"

---
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}

## Managing service access roles
{: #managing-service-access-roles}

You can secure services within {{site.data.keyword.Bluemix_notm}} by allowing only users with specified access roles to complete certain actions.
{: shortdesc}

### Platform access roles
{: #platform-access-roles}

You can use either platform access roles or service access roles to define the access role for users in your IBM Cloud account.

<table>
<caption> Table 1. Actions that are mapped to platform access roles</caption>
  <tr>
    <th> Action </th>
    <th> Role </th>
  </tr>
  <tr>
    <td>List certificates</td>
    <td> Administrator, Operator, Editor, Viewer </td>
  </tr>
  <tr>
    <td>Download a certificate and private key </td>
    <td> Administrator, Operator </td>
  </tr>
  <tr>
    <td>Update certificate metadata</td>
    <td> Administrator, Editor </td>
  </tr>
  <tr>
    <td>Upload certificates, private keys, and intermediate certificates </td>
    <td> Administrator, Editor  </td>
  </tr>
  <tr>
    <td>Delete a certificate and private key </td>
    <td> Administrator, Editor </td>
  </tr>
</table>

### Service access roles
{: #service-acceess-roles}

<table>
<caption> Table 2. Actions that are mapped to service access roles</caption>
  <tr>
    <th> Action </th>
    <th> Role </th>
  </tr>
  <tr>
    <td>List certificates</td>
    <td> Manager, Writer, Reader </td>
  </tr>
  <tr>
    <td>Download a certificate and private key </td>
    <td> Manager, Writer </td>
  </tr>
  <tr>
    <td>Update certificate data</td>
    <td> Manager, Writer </td>
  </tr>
  <tr>
    <td>Upload certificates, private keys, and intermediate certificates </td>
    <td> Manager  </td>
  </tr>
  <tr>
    <td>Delete a certificate and private key </td>
    <td> Manager </td>
  </tr>
</table>

For more information about user roles and permissions, see [User roles](/docs/iam/users_roles.html#userroles).

### Assigning user access roles
{: #assigning-user--access-roles}

To assign an access role on the account-level or resource group-level, complete the following steps.
If the user is not part of your organization, start by sending an invitation to that user.

1. Go to **Manage > Account > Users**.
2. From the **Actions** menu, select **Assign policy**.
3. Click **Assign access to resources** or **Assign access within a resource group**.
4. Under **Services**, select **Certificate Manager**.
5. Optional: Select a **Region** or use the default, **All regions**.
6. Optional: Select a **Service instance** or use the default, **All instances**.
7. Under **Select roles > Assign platform/service access roles**, select the appropriate access level.