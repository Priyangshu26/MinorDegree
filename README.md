# Secure Systems Study Hub

A lightweight, responsive study website for the five syllabus modules from **Advanced System Security Topics** (University of Colorado System, Coursera). It presents the notes as short explanations, readable bullet points, examples, definitions, and practice questions.

## Open the study hub

Open [`index.html`](./index.html) in a modern web browser. The site is built with plain HTML, CSS, and JavaScript, so it does not need a build step or package installation.

## Modules

1. **Introduction to Access Control** — subjects, resources, actions, policies, authentication, authorization, auditing, principles, RBAC, and ABAC.
2. **Policies, Models, and Mechanisms** — DAC, non-discretionary access control, MAC, ACLs, and capability lists.
3. **Role-Based Access Control** — core and hierarchical RBAC, static and dynamic constraints, limitations, and enterprise examples for workflow systems, UNIX, and Java.
4. **Smart Card Security** — operating systems, design principles, memory and files, user identification, security techniques, testing, the five life-cycle phases, PPS, and terminals.
5. **Cloud Data Security and Audit** — database access control, current security approaches, data audits, audit practices, key management, and cloud key-management audits.

Each module includes an exam-ready summary and review questions. Abbreviations are expanded in the notes, and each topic begins with a short definition.

## Publish a public study link

To share the site with friends, publish this folder with GitHub Pages:

1. Create a **public** GitHub repository.
2. Upload `index.html` and `README.md` to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select the default branch and `/ (root)`, then save.
5. GitHub will show the public Pages URL in the Pages settings once deployment finishes.

The website itself is static and has no server-side components. Google Fonts is loaded from the web; if you prefer a fully offline page, remove the font import at the top of `index.html` and the browser will use its fallback fonts.

## Note

These are study notes prepared from the supplied syllabus topics and our conversation. Use your course materials and instructor guidance as the final reference for exam expectations.
