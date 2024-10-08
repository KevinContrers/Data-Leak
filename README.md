# Cybersecurity Analysis: Data Leak and Principle of Least Privilege 

## Scenario

As part of my hands-on training through the **Google Cybersecurity Professional Certificate**, I investigated a **data leak** incident within an educational technology company. A sales representative mistakenly shared confidential internal business documents with an external partner, who then inadvertently posted the documents on social media. My task was to analyze the situation and find ways to prevent such incidents from happening in the future.

---

## Incident Summary

The leak occurred during a sales meeting where a sales manager granted access to an internal folder containing sensitive business plans, customer analytics, and promotional materials. The **Principle of Least Privilege** was not enforced, leading to inappropriate access by the sales team. After the meeting, a sales representative mistakenly shared the entire folder with a business partner, who then posted it on their company's social media page, believing it was promotional material.

| **Issue Identified**       | **Description**                                                                 |
|----------------------------|---------------------------------------------------------------------------------|
| Lack of Access Controls     | Sensitive internal documents were shared beyond the necessary personnel.        |
| Accidental Sharing          | A sales representative unintentionally shared the internal folder with an external party. |

---

## Control Review

According to **NIST SP 800-53: AC-6** (Least Privilege), users should be granted only the minimal access necessary to complete tasks. This principle was not adhered to, as the sales team had broader access to sensitive files than necessary.

### Key Controls for Preventing Data Leaks

1. **Restrict Access Based on Roles**  
   Implement strict role-based access control (RBAC) to ensure only authorized personnel can view or share sensitive documents.
   
2. **Audit User Privileges Regularly**  
   Regularly audit user access to ensure that permissions align with their job roles and responsibilities.

---

## Recommendations

To improve information privacy and prevent future data leaks, I recommend the following steps:

| **Recommendation**              | **Justification**                                                                                 |
|----------------------------------|---------------------------------------------------------------------------------------------------|
| **Role-Based Access Control (RBAC)** | Limit access to sensitive information based on specific roles to ensure the principle of least privilege. |
| **Regular Audits**               | Conduct regular audits of user privileges to identify and revoke unnecessary access.               |
| **Automated Access Revocation**  | Implement automatic revocation of access rights after a defined period to prevent accidental data leaks. |
| **User Training**                | Provide security training to employees on the importance of safeguarding sensitive information.    |

These measures will help ensure that access to sensitive information is properly restricted, reducing the risk of accidental data leaks and protecting the company’s critical assets.

---

## Learning and Experience

This project highlighted the importance of enforcing the **Principle of Least Privilege** and maintaining strict access controls to prevent data breaches. By regularly auditing user access and implementing role-based access control (RBAC), organizations can minimize the chances of accidental leaks and ensure sensitive data is shared only with authorized personnel.

---

## Tools & Technologies Used

| **Tool/Technology**        | **Purpose**                                                      |
|----------------------------|------------------------------------------------------------------|
| **NIST SP 800-53 AC-6**     | Provided guidelines for implementing least privilege access control. |
| **Role-Based Access Control** | Restricted access to sensitive resources based on user roles.     |

---

This hands-on project provided valuable insights into safeguarding sensitive data by ensuring that access controls align with an organization’s security policies. The exercise reinforced the importance of **least privilege** and the role of regular audits in preventing data breaches.

---
