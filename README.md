# Food & Drink Ranker

A shared, real-time food and drink vendor ranking site, built as a single self-contained file. No build tools or frameworks required. 

## Features

- Half-star ratings: tap or drag across the stars to rate.
- Vendor details: name, dish/item, address, and an optional link to the vendor's website.
- Notes: optimal text field for notes.
- Real-time sync: powered by [Supabase](https://supabase.com). Entries update live for everyone viewing the page. Everything lives in Supabase, so the list is consistent across devices and visitors.
- Password-protected editing: anyone can view and sort the list, but adding or deleting entries requires a password. The password unlock is remembered for the current browser session only, and resets when the tab is closed.
