# Vendor.Watch Content Repository

This repository contains all the public-facing content for the Vendor.Watch platform, managed through Keystatic CMS.

## Content Structure

- `content/posts/` - Blog posts and articles
- `content/documentation/` - User guides and documentation
- `content/site/` - Static site content (when needed)

## Current Content

### Blog Posts
- **Why Would You Accept?** - Understanding vendor acceptance criteria
- **A New Level of Transparency in Personal Data Flows** - Data transparency insights
- **Survival Mode** - Vendor risk management strategies

### Documentation
- **Getting Started** - Installation and setup guides
- **Authentication** - User authentication and configuration

## How It Works

1. **Content Creation**: Use Keystatic CMS admin interface at `/keystatic`
2. **Automatic Commits**: Changes are automatically committed to this repository
3. **Webhook Triggers**: GitHub webhooks notify the main application
4. **ISR Revalidation**: Pages are automatically regenerated with new content
5. **Live Updates**: Users see updated content immediately

## Content Guidelines

- Use Markdown format for all content
- Include proper frontmatter metadata as defined in Keystatic schema
- Follow the established content structure
- Test content through the Keystatic admin interface
- All content should be public-facing (no internal project docs)

## Collaboration

Multiple content creators can work simultaneously:
- Create feature branches for major changes
- Use pull requests for content review
- Merge to main branch for live updates
- All changes are tracked in Git history

## Migration Notes

This content was migrated from the main Vendor.Watch project on August 12, 2024. The content structure has been preserved to maintain compatibility with the existing Keystatic configuration.

## Support

For questions about content management, contact the development team through the main project repository.
