# Email Deliverability Checklist 📬

**A practical guide to helping marketing emails reach the inbox.**

You can spend hours writing the perfect email, designing a beautiful template, and building a campaign. But if your emails aren't reaching the inbox, your audience may never see the work you've put into them.

Email deliverability deserves just as much attention as email content.

I created this checklist to bring the essential checks together in one place. From domain authentication and list hygiene to email QA and post-send monitoring.

## What's Inside

- [ ] Email authentication and domain alignment
- [ ] Sender reputation and sending practices
- [ ] Email list hygiene and segmentation
- [ ] Content quality and email QA
- [ ] Technical checks and compliance
- [ ] Post-send monitoring and optimization

## 01. Email Authentication 🔐

Authentication helps receiving email providers verify that messages are authorized to come from your domain.

- [ ] **SPF:** Verify that your SPF record authorizes the appropriate sending services.
- [ ] **DKIM:** Configure DKIM signing and verify that signatures pass.
- [ ] **DMARC:** Publish a DMARC policy and review authentication reports where available.
- [ ] **Domain alignment:** Check that the authenticated domain aligns with the visible From domain as required by DMARC.
- [ ] **Branded sending domain:** Use a domain you own and can authenticate.
- [ ] **Verification:** Test authentication after making DNS changes.

**My takeaway:** Don't assume your setup is correct just because your email platform is connected. Verify it.

## 02. Sender Reputation 📈

Your sending reputation is influenced by sending practices and recipient responses over time.

- [ ] **Ramp up new sending infrastructure carefully.** Start with legitimate, opted-in audiences and monitor results as volume grows.
- [ ] **Send to people who expect your emails.** Avoid poorly sourced or outdated contact lists.
- [ ] **Monitor spam complaints.** Investigate increases instead of treating them as normal.
- [ ] **Review reputation signals.** Use tools such as Google Postmaster Tools where applicable, and investigate relevant blocklist listings when needed.
- [ ] **Watch bounce trends.** Identify sudden increases and investigate the cause.
- [ ] **Choose an appropriate ESP.** Evaluate authentication support, suppression management, reporting, and compliance features.

**Remember:** No warm-up tool or sending strategy can guarantee inbox placement.

## 03. Email List Hygiene 🧹

A bigger list isn't necessarily a better list. Focus on reaching the right audience with messages they expect and find useful.

- [ ] **Suppress hard bounces.** Prevent future sends to addresses that have permanently failed.
- [ ] **Investigate soft bounces.** Look for recurring temporary delivery issues before deciding what action to take.
- [ ] **Review inactive subscribers.** Use an appropriate engagement window based on sending frequency and buying cycle.
- [ ] **Look beyond opens.** Consider clicks, conversions, replies, and other meaningful engagement signals.
- [ ] **Use re-engagement campaigns selectively.** Give eligible inactive contacts a relevant reason to engage again.
- [ ] **Segment your audience.** Consider lifecycle stage, interests, customer status, and relevant behaviour.
- [ ] **Respect subscription preferences.** Apply suppression lists and opt-out requirements before sending.
- [ ] **Avoid purchased or scraped lists.** These can increase the risk of invalid addresses, complaints, and compliance problems.

**My takeaway:** The goal isn't to email everyone. It's to email the right people.

## 04. Email Content and Quality Assurance ✉️

Content alone doesn't determine deliverability, but misleading or irrelevant emails can damage recipient trust.

- [ ] **Write honest subject lines.** Make sure the subject reflects the actual email.
- [ ] **Keep messaging relevant.** Personalization should improve the experience, not just insert a first name.
- [ ] **Use a recognizable sender identity.** Keep your From name consistent and use a monitored reply-to address where possible.
- [ ] **Include an easy unsubscribe option.** Make opting out straightforward.
- [ ] **Test every link.** Check destinations, redirects, tracking parameters, and calls to action.
- [ ] **Optimize images thoughtfully.** Add alt text and ensure the email remains understandable when images are blocked.
- [ ] **Check mobile rendering.** Review layout, font sizes, buttons, and spacing on smaller screens.
- [ ] **Validate personalization.** Test tokens, fallback values, and conditional content.
- [ ] **Review the HTML and plain-text version.** Check readability, accessibility, and rendering.

**My takeaway:** If an email makes a promise, the content and landing page should deliver on it.

## 05. Technical and Compliance Checks ⚙️

A few overlooked details can create unnecessary problems on launch day.

- [ ] **Confirm the sending configuration.** Check the intended From address, sending domain, and authentication.
- [ ] **Review suppression settings.** Ensure unsubscribes, hard bounces, and other required exclusions are respected.
- [ ] **Check sender information.** Include the identification and contact details required for your campaigns.
- [ ] **Verify unsubscribe mechanisms.** Implement one-click unsubscribe where required by the applicable provider rules.
- [ ] **Review consent and legal requirements.** Requirements vary by jurisdiction, audience, and campaign type.
- [ ] **Check sending frequency.** Make sure it matches audience expectations and your normal sending patterns.
- [ ] **Run a final test.** Verify links, personalization, rendering, recipients, and exclusions before launch.

## 06. Post-Send Monitoring 🔎

Deliverability work doesn't stop when a campaign is sent. Review what happened and use the findings to guide your next action.

| Metric | What to investigate |
|---|---|
| Delivery and bounce rates | Unexpected changes, invalid addresses, and receiving-server issues |
| Click-through rate | Engagement with the email's content and calls to action |
| Conversions | Whether the campaign achieved its intended outcome |
| Spam complaints | Audience relevance, expectations, and sending practices |
| Unsubscribes | Frequency, content relevance, and audience fit |
| Inbox placement | Whether messages are reaching inboxes or spam folders in the environments tested |

- [ ] Compare performance with relevant historical campaigns.
- [ ] Review results by audience segment where possible.
- [ ] Investigate unusual delivery or engagement changes.
- [ ] Document the issue, action taken, and subsequent results.
- [ ] Use the findings to improve the next campaign.

**My takeaway:** Don't just report the numbers. Understand what they mean and decide what to do next.

## My Pre-Send Checklist

Before launching a campaign, confirm that:

- [ ] Email authentication has been checked.
- [ ] The audience is appropriate for the campaign.
- [ ] Suppression lists and subscription preferences have been reviewed.
- [ ] Bounce and complaint signals are being monitored.
- [ ] The subject line and sender identity are accurate.
- [ ] Links, personalization, and dynamic content have been tested.
- [ ] Mobile rendering and accessibility have been reviewed.
- [ ] Unsubscribe and applicable compliance requirements are covered.
- [ ] Recent delivery and engagement trends have been reviewed.
- [ ] A post-send monitoring plan is in place.

## Final Thoughts

Deliverability isn't a one-time setup task. It's an ongoing process that combines authentication, list quality, recipient expectations, responsible sending practices, and performance monitoring.

No checklist can guarantee inbox placement, but a consistent process can help identify issues earlier and support better decisions.

I'd rather catch a problem before a campaign goes out than spend the next few days trying to figure out why performance dropped.

### About This Project

This is an educational portfolio resource demonstrating my approach to email marketing operations, campaign QA, and deliverability best practices.

**Focus areas:** Email Marketing · Marketing Operations · Campaign QA · Optimization

