---
sidebar_position: 2
slug: /manage_team_members
---

# Manage team members

Invite or remove team members.

---

By default, each RAGFlow user is assigned a single team named after their name. RAGFlow allows you to invite RAGFlow users to your team with different roles. Your team members can help you:

- Upload documents to your shared datasets (knowledge bases).
- Parse documents in your shared datasets.
- Use your shared Agents.

## Team Roles

RAGFlow supports the following team roles:

- **Owner**: Full control over the team, including inviting/removing members, managing roles, and deleting the team.
- **Admin**: Can invite and remove team members, access all team resources, but cannot delete the team or change member roles.
- **Normal**: Basic team member with access to shared resources based on permissions.

:::tip NOTE
- Team admins can invite users to your team and manage team members.
- Only the team owner can promote members to admin or change member roles.
- Sharing added models with team members is only available in RAGFlow's Enterprise edition.
:::

## Prerequisites

1. Ensure that the invited team member is a RAGFlow user and that the Email address used is associated with a RAGFlow user account.
2. To allow your team members to view and update your knowledge base, ensure that you set **Permissions** on its **Configuration** page from **Only me** to **Team**.

## Invite team members

Click on your avatar in the top right corner of the page, then select **Team** in the left-hand panel to access the **Team** page.

![team](https://github.com/user-attachments/assets/0eac2503-26bc-4568-b3f2-bcd84069a07a)

_On the **Team** page, you can view the information about members of your team and the teams you have joined._

You are, by default, the owner of your own team and the only person permitted to invite users to join your team or remove team members.

![invite_team_member](https://github.com/user-attachments/assets/d85b55c3-7e86-4f04-a414-ca18a9ee8963)

## Remove team members

![remove_members](https://github.com/user-attachments/assets/5c1a6ab5-8862-47a0-ad09-77fe88866508)

## Manage team member roles

As the team owner, you can promote team members to admin or change their roles:

1. On the **Team** page, locate the team member whose role you want to change.
2. Use the role management interface to select the desired role:
   - **Admin**: Grants the member ability to invite/remove users and access all team resources
   - **Normal**: Standard team member with basic access to shared resources

:::tip NOTE
- Only team owners can change member roles
- Admin members cannot change roles of other members
- The owner role cannot be transferred or changed
:::