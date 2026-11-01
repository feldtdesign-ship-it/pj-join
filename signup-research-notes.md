# Sign-up research: what's worth keeping

Sorted 2026-11-01 from a Gemini research paste on lead capture and email sign-up.
Most of it was written for B2B "project update" lists. These are the parts that apply to PJ.

## Keep

1. **Short form.** Only email is required. pj-join already does this (IG, phone, birthday optional).
2. **Ask more later, not up front.** The PJ's Pick vote and the "Which stop are you?" quiz already do this. Save every answer as a **customer tag** so emails can use it later.
3. **Button says what you get.** "Get my Lost & Found card", not "Sign up".
4. **Separate unticked box for texts.** US text-message rules are stricter than email. (My addition: the research only covered email law.)
5. **Invisible spam trap.** A hidden field that bots fill in and people never see. No CAPTCHA. Check whether Shopify's own forms already cover this (not verified).
6. **Welcome email right away, second email ~3 days later** with one-tap links ("pick your favorite drop"). Each tap adds a tag. Shopify Email or Klaviyo flows.
7. **Two numbers to watch:** spam complaints under **0.3%**, bounces under **2%**. Above those, Gmail and Yahoo start sending PJ's mail to spam.

**Setup check:** PJ's own domain verified as the sender in Shopify. That one step covers the SPF / DKIM / DMARC section.

## Skip

- **Email platform comparison.** HubSpot, ActiveCampaign, Customer.io are B2B sales tools. The real choice for PJ is **Shopify Email vs Klaviyo**.
- **Code samples.** Generic business form. The spam check runs in the browser (bots skip it) and shows real customers a "too fast" error.
- **Unsubscribe headers and DNS details.** The email platform handles these.
- **EU / Canada law table.** PJ's customers are mostly US. Only the unticked box (#4) carries over.
- **Double opt-in.** The research says it loses 15–25% of sign-ups, and the email list is PJ's gap. Plain single sign-up for email.
- **"120% higher conversion" stat.** Marketing-blog number, not verified. Don't quote it to PJ.
