# CodewithAlbin Blogger Theme Deployment

1. Open Blogger and go to `Theme`.
2. Use the dropdown next to `Customize`, then choose `Edit HTML`.
3. Replace the existing markup with the contents of [theme.xml](D:\Albin-WorkSpace\GitHub\Personal\Albin_Blogger_Src\theme.xml).
4. Save the theme.
5. Create these static pages in Blogger so the navigation matches the theme:
   - `Blog`
   - `About Me`
   - `Projects`
   - `Resume`
   - `Services`
   - `Resources`
   - `Testimonials`
   - `Contact`
6. Replace placeholder links for:
   - Resume PDF
   - GitHub
   - LinkedIn
   - Email
7. Publish posts using these core labels:
   - `ASP.NET Core`
   - `Web APIs`
   - `Microservices`
   - `System Design`
   - `Cloud`
   - `Frontend`
   - `DevOps`
   - `Interview Prep`
   - `Career & Freelancing`
8. Add post-type labels when relevant:
   - `Tutorials`
   - `Deep Dives`
   - `Case Studies`
   - `Project Builds`
   - `Code Snippets`
9. For blog series support, use labels like `Series:Microservices` or `Series:SystemDesign`.
10. Use proper `h2` and `h3` headings inside posts so the auto-generated table of contents works well.

## Notes

- Search uses Blogger’s native `/search` experience.
- Comments use Blogger’s default comment system.
- The newsletter block is UI-only and ready for a future email provider.
- Dark mode is default, and the visitor’s theme preference is stored locally.
- Optimize images before uploading them to Blogger for the best performance score.
