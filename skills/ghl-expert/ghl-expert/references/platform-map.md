# GHL Platform Feature Map

Complete reference of GoHighLevel's feature areas, organized by category. Use this to navigate questions to the right area and understand how features relate to each other.

## Core CRM
- **Contacts**: Create, edit, bulk actions, merge duplicates, DND (Do Not Disturb) settings
- **Custom Fields**: Text, number, date, dropdown, checkbox, file upload, signature — available on contacts, opportunities, and companies
- **Tags**: Manual or automation-applied labels for segmentation
- **Smart Lists**: Dynamic contact lists based on filter criteria (tags, fields, activity, dates)
- **Companies**: B2B entity associated with contacts (newer feature)
- **Tasks**: Assignable to-do items linked to contacts
- **Notes**: Free-text notes on contact records
- **Import/Export**: CSV import with field mapping, CSV/Excel export

## Communication (Conversations)
The unified inbox aggregates all channels into one view per contact:
- **SMS/MMS**: Via LC Phone or own Twilio. Subject to A2P/10DLC compliance
- **Email**: Via LC Email (Mailgun) or connected SMTP/Google/Outlook
- **Phone**: Inbound/outbound calls, call recording, voicemail drops, Power Dialer, call transfer
- **WhatsApp**: Business API integration (requires Meta approval)
- **Facebook Messenger**: Requires connected Facebook page
- **Instagram DM**: Requires connected Instagram business account
- **Google Business Messages**: Via Google Business Profile
- **Live Chat Widget**: Embeddable chat widget for websites/funnels
- **Reviews**: Inbound review notifications appear in conversations

## Sales Pipeline
- **Pipelines**: Multiple pipelines allowed, each with custom stages
- **Opportunities**: Individual deals/leads tracked on pipelines
- **Stages**: Customizable columns (e.g., New Lead → Qualified → Proposal → Won/Lost)
- **Manual Actions**: Tasks that must be completed before moving to next stage
- **Pipeline Automations**: Workflow triggers based on stage changes
- **Opportunity Custom Fields**: Deal-specific data fields
- **Pipeline Value**: Monetary tracking of deal values

## Scheduling (Calendars)
- **Event Calendar**: 1-on-1 appointments with a single team member
- **Round Robin**: Auto-distributes bookings among team members (equal distribution, optimize for availability, or priority-based)
- **Class Booking**: Group events with capacity limits
- **Collective Booking**: Requires availability of multiple team members simultaneously
- **Service Calendar**: Menu of services with different durations/prices
- **Booking Widget**: Embeddable calendar for websites/funnels
- **Google Calendar Sync**: Two-way sync to prevent double-booking
- **Outlook Calendar Sync**: Two-way sync
- **Calendar Groups**: Display multiple calendars on one booking page
- **Buffer Time**: Configurable gaps between appointments
- **Office Hours**: Availability windows per team member

## Marketing
- **Funnels**: Multi-step page builder (landing page → form → thank you). Drag-and-drop editor with sections, rows, columns, elements
- **Websites**: Full website builder (newer, distinct from funnels)
- **Landing Pages**: Standalone pages within funnels
- **Forms**: Lead capture forms (embeddable or within funnels). Custom fields, conditional logic
- **Surveys**: Multi-step forms with scoring and conditional logic
- **Social Planner**: Schedule posts to Facebook, Instagram, Google Business, LinkedIn, TikTok, X/Twitter
- **Blog**: Built-in blogging with SEO settings
- **Email Campaigns**: Broadcast emails to segments. HTML editor or template-based
- **SMS Campaigns**: Broadcast SMS to segments
- **Templates**: Email, SMS, workflow, funnel, and website templates

## Automation (Workflows)
Workflows are the heart of GHL automation — a visual builder with triggers, actions, and logic:

**Common Triggers**: Contact created, form submitted, tag added/removed, appointment booked/cancelled, opportunity stage changed, invoice paid, call status changed, custom webhook received, birthday/date field, contact DND, manual trigger

**Common Actions**: Send SMS, send email, send voicemail drop, create task, add/remove tag, add to workflow, remove from workflow, update contact field, create opportunity, update opportunity, send webhook, wait (time delay or until condition), if/else branch, go to, internal notification, assign user, add to Google Sheet

**Logic**: If/Else conditions (based on contact fields, tags, time, activity), Go To (loop or skip), Wait (fixed time, until date, until condition), Math operations

**Best Practices**: Always test with a test contact. Check execution logs for errors. Use descriptive action names. Be careful with webhook timeouts. Remember workflows must be published (toggled on) to run.

## Payments
- **Payment Processors**: Stripe (primary), PayPal, Square, Authorize.net, NMI
- **Products**: Physical, digital, or service products with prices
- **Order Forms**: Checkout pages (within funnels or standalone)
- **Invoices**: One-time or recurring billing
- **Subscriptions**: Recurring payment plans
- **Coupons**: Percentage or fixed discount codes
- **Taxes**: Configurable tax rates

## Content / Courses
- **Courses**: Full course builder with modules and lessons (video, text, files)
- **Memberships**: Gated content areas tied to products/offers
- **Communities**: Discussion forums/groups for members
- **Certificates**: Auto-generated completion certificates
- **Drip Content**: Time-released course content
- **Offers**: Bundled access to courses/memberships with pricing

## Reputation Management
- **Review Requests**: Automated SMS/email asking for Google/Facebook reviews
- **Review Widget**: Embeddable widget showing reviews on websites
- **Review Monitoring**: Centralized view of reviews across platforms
- **AI Review Responses**: Auto-generated review reply suggestions

## Reporting & Analytics
- **Dashboard**: Overview metrics (contacts, appointments, pipeline value, revenue)
- **Attribution**: Track lead sources and conversion paths
- **Call Reporting**: Call duration, recordings, outcomes, agent performance
- **Ad Reporting**: Facebook/Google ad performance within GHL
- **Appointment Reports**: Booking rates, no-show rates, calendar performance
- **Funnel/Website Analytics**: Page views, conversion rates, form submissions

## Agency Features
- **SaaS Mode**: White-label GHL as your own platform (requires $297+ plan)
- **SaaS Configurator**: Set feature access, limits, and pricing for sub-accounts
- **White-labeling**: Custom domain, logo, colors, email headers for your branded platform
- **Sub-accounts (Locations)**: Individual client workspaces within your agency account
- **Snapshots**: Full sub-account configuration templates — capture and deploy workflows, funnels, pipelines, tags, etc. across sub-accounts
- **Prospecting Tool**: Find leads for your agency using business data
- **Agency Dashboard**: Overview of all sub-accounts, revenue, usage
- **Rebilling**: Mark up GHL usage costs (phone, email, AI) and charge sub-accounts
- **Marketplace**: Build and sell apps/integrations to other GHL users

## Phone/SMS Compliance
- **A2P 10DLC Registration**: Required for US SMS. Register brand and campaign through GHL. Takes days-to-weeks. Rejection requires resubmission with better descriptions
- **Toll-Free Verification**: Separate process from 10DLC
- **LC Phone vs Own Twilio**: LC Phone is simpler but less control. Own Twilio gives more control, potentially better pricing at scale, but more setup
- **Number Porting**: Bring existing numbers into GHL/LC Phone
- **TCPA Compliance**: Consent management, opt-out handling, DND lists

## AI Features (Rapidly Evolving)
- **Conversation AI**: AI chatbot within conversations — can qualify leads, answer FAQs, book appointments
- **Voice AI**: AI phone agent for inbound/outbound calls — configurable scripts, can transfer to humans
- **Content AI**: Writing assistant for emails, funnels, social posts, SMS
- **Reviews AI**: Auto-generates review response drafts
- **Workflow AI**: AI-powered actions within workflows (summarize conversations, classify intent, generate personalized content)
- **Image AI**: AI image generation for marketing content
These features have separate pricing and are updated frequently. Always check current docs.

## Integrations
- **Zapier**: 1000+ app connections via triggers and actions
- **Make (Integromat)**: Alternative automation platform integration
- **Pabbly**: Budget alternative to Zapier
- **Google**: Calendar, GMB, Ads, Analytics, Sheets
- **Facebook/Meta**: Pages, Messenger, Instagram, Lead Ads, Conversions API
- **Stripe**: Primary payment processor
- **QuickBooks**: Accounting sync
- **Yext**: Listings management
- **Shopify**: E-commerce sync
- **Custom Webhooks**: Inbound and outbound webhook support
- **API v2**: Full REST API with OAuth 2.0
- **Marketplace Apps**: Third-party apps built on GHL's platform
