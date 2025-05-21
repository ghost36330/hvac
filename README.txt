# Austin Industrial HVAC Maintenance Website

This website allows technicians to submit pre-maintenance checks via an embedded Google Form and provides an admin dashboard with charts visualizing the data from Google Sheets.

## Files

- `index.html`: Public page embedding the Google Form for data entry  
- `admin.html`: Admin dashboard page showing charts, protected by an admin code (`1695`)

## Deployment

- Hosted on Netlify (or your preferred static host)  
- No backend required; all data comes from Google Forms/Sheets  
- To update the site, modify the HTML files and redeploy

## Admin Access

- Admin dashboard requires code `1695` to view  
- Modify the admin code in `admin.html` if needed (search for `ADMIN_CODE`)

## Notes

- Make sure the Google Sheets data is shared with “Anyone with the link can view” to allow chart fetching  
