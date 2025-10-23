# KZNERA Logo Setup Instructions

## Adding the Logo to Your Presentation

To complete the presentation setup, you need to add the KZNERA logo image to your repository:

### Method 1: Direct Upload (Recommended)

1. **Save the KZNERA logo image** as `kznera-logo.png` (the image you provided)
2. **Upload to your repository**:
   - Go to https://github.com/ChimenyaDev/OnlineLiquorPortal
   - Click "Add file" → "Upload files"
   - Drag and drop `kznera-logo.png`
   - Commit the file to the main branch

### Method 2: Using Git Command Line

```bash
# Navigate to your repository
cd OnlineLiquorPortal

# Add the logo image (make sure it's named kznera-logo.png)
git add kznera-logo.png

# Commit and push
git commit -m "Add KZNERA logo to presentation"
git push origin main
```

## Brand Colors Applied

The presentation now uses the official KZNERA brand colors extracted from your logo:

- **Primary (Dark Blue)**: `#003D5C` - Main headings, navigation, backgrounds
- **Secondary (Green)**: `#00A651` - Accents, progress bars, stakeholder cards
- **Accent (Orange/Gold)**: `#F7941D` - Borders, highlights, call-to-actions

## Logo Placement

The logo has been professionally positioned:

1. **Title Slide**: Large centered logo (200px height) at the top, with white filter for dark background
2. **Content Slides**: Small logo (80px height) in top-left corner for brand consistency
3. **Responsive sizing**: Maintains aspect ratio across all screen sizes

## File Requirements

- **File name**: Must be exactly `kznera-logo.png`
- **File location**: Root directory of the repository
- **Recommended format**: PNG with transparent background (if available)
- **Recommended size**: At least 500x500px for quality scaling

## Troubleshooting

If the logo doesn't appear:

1. Verify the file is named exactly `kznera-logo.png` (case-sensitive)
2. Ensure the file is in the root directory (same location as `index.html`)
3. Clear your browser cache and reload the page
4. Check that the image uploaded successfully to GitHub

## Alternative: Using External URL

If you host the logo elsewhere, update line references in `index.html`:

```html
<!-- Replace all instances of -->
<img src="kznera-logo.png" alt="KZNERA Logo">

<!-- With your hosted URL -->
<img src="https://your-cdn.com/kznera-logo.png" alt="KZNERA Logo">
```