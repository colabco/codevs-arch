# 🛠️Tooling Choices
These should not be taken as "X is better than Y" doctrine. A lot of these are simply canted towards industry and marketplace dictates.
Ultimately, choose the best tooling for the task at hand

## Repository Management & Version Control
- Prefer github for now.

## Roadmapping and cross-discipline / high-level issues management
- No preference: JIRA, Trello, Excel; whatever works.

## Application-specific Issue Management
- prefer JIRA for PO/PM-led issue management
- prefer Github issues for Developer/Engineering-led issue management
- Prefering the chosen roadmapping / high level requirements management tool for non- developer-specific tasks is OK

## Cloud Platforms
- prefer AWS for infra & devOps specific goals. All other providers OK for general purposes.

## Developer Platforms / Operating Environments
Guidelines
- prefer linux / WSL / mac over windows development environments
- maintain unix line-endings for all codebases
:warning: this means if you are using vs-code on windows, your **MUST** use WSL. If that's not possible, use a cloud IDE.

## Data Ecosystem
- Prefer postgres over mysql over other engines for RDBMS
- Prefer redis for key-value pair stores
- No particular preference wrt NOSQL databases: MongoDB, DynamoDB, etc all ok.

## Node JS Ecosystem
Guidelines
- prefer installation of nodejs via **nvm** versus direct installation of node.
- prefer **node 20+** as much as possible to stay abreast of latest developments
- prefer **pnpm** over npm/yarn where possible; pnpm is a mouthful but it's better for disk space.
- prefer using **typescript** over vanilla javascript as much as possible for maintainability and type safety.
