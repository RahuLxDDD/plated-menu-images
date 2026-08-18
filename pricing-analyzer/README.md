# Menu Price Analyzer

Browser-first MVP for restaurant dine-in to Zomato pricing analysis.

## Supported input
- CSV
- XLSX / XLS
- PDF (text extraction, OCR fallback)
- PNG / JPG / JPEG (OCR)

## Output
- Spreadsheet uploads: analyzed CSV/XLSX with added recommendation columns
- PDF/image uploads: structured XLSX analysis

## Current logic
- Commercial inputs: commission, payment gateway, GST on commission, discount, Ads/CV, promo/Growmax, target payout
- Pricing modes: Safe, Balanced, Aggressive
- Category-aware uplift caps for low-ticket dry items, beverages, mains, hero items and normal items
- Price-ending rules: 9 / 5 / 0
- Flags: Safe, Watch, Review
- Editable recommended prices before export

## Important
This is a decision-support tool, not an official Zomato pricing system. Pricing recommendations should be reviewed before publishing.

## Next milestones
1. Upload both Dine-in and Current Zomato menus and fuzzy-match items
2. Add item-level payout simulator
3. Better multi-column menu OCR and category detection
4. Preserve workbook structure/styles more faithfully
5. Restaurant-level summary and merchant pitch report
