# Image Upload Guide for Admins

Since this is a static website without a backend server, images need to be hosted externally and linked via URL. Here's how to add images for leaders, events, and other content:

## Recommended Image Hosting Services (Free)

### 1. Imgur (Easiest, Recommended)
1. Go to https://imgur.com
2. Click "New post" or drag image to the page
3. Upload completes automatically
4. Right-click on the uploaded image
5. Select "Copy image address" or "Copy image location"
6. Paste this URL in the admin panel

**Example URL**: `https://i.imgur.com/ABC123.jpg`

### 2. ImgBB
1. Go to https://imgbb.com
2. Click "Start uploading"
3. Select or drag your image
4. After upload, click "Direct link"
5. Copy the URL
6. Paste in the admin panel

**Example URL**: `https://i.ibb.co/ABC123/image.jpg`

### 3. GitHub (For Advanced Users)
1. Create a public GitHub repository for images
2. Upload images to the repository
3. Navigate to the image file
4. Click "Raw" button
5. Copy the URL
6. Paste in the admin panel

**Example URL**: `https://raw.githubusercontent.com/username/repo/main/image.jpg`

### 4. Google Drive (Public Link)
1. Upload image to Google Drive
2. Right-click → Get link
3. Change to "Anyone with the link can view"
4. Copy link
5. Convert to direct link format (see below)

**Note**: Google Drive links need conversion. Use a service like https://www.labnol.org/google-drive-direct-download

## Image Requirements

### Leader Photos
- **Format**: JPG or PNG
- **Recommended size**: 400x400 pixels (square)
- **Max file size**: 2 MB
- **Aspect ratio**: 1:1 (square) looks best

### Event Images
- **Format**: JPG or PNG
- **Recommended size**: 1200x675 pixels (landscape)
- **Aspect ratio**: 16:9 looks best
- **Max file size**: 3 MB

### Logo
- **Format**: PNG (with transparency) or JPG
- **Recommended size**: 200x200 pixels or larger
- **Should work on both light and dark backgrounds**

### Publication Images (Newspaper Clippings)
- **Format**: JPG or PNG
- **Recommended size**: 800x600 pixels or larger
- **Should be readable when displayed**

## Step-by-Step: Adding a Leader Photo

1. **Prepare the image**:
   - Crop to square (1:1 aspect ratio)
   - Resize to 400x400 pixels if large
   - Save as JPG or PNG

2. **Upload to Imgur**:
   - Go to https://imgur.com
   - Drag and drop your image
   - Wait for upload to complete

3. **Get the direct link**:
   - Right-click on the uploaded image
   - Select "Copy image address"
   - URL should look like: `https://i.imgur.com/ABC123.jpg`

4. **Add to website**:
   - Open Admin Panel on your website
   - Go to Leadership tab
   - Click "Add New Leader" or edit existing
   - Paste URL in "Photo URL" field
   - Preview shows immediately
   - Click "Add Leader" or "Update"

## Troubleshooting

### Image doesn't show up
- ✅ Verify URL ends in .jpg, .png, .gif, or .webp
- ✅ Try opening URL directly in browser
- ✅ Check if hosting service blocks embedding
- ✅ Ensure URL starts with https://

### Image shows but is too large/small
- The website automatically resizes images
- For best quality, use recommended sizes above
- Larger images take longer to load

### Image shows broken icon
- URL might be incorrect
- Image might have been deleted from hosting service
- Try re-uploading and getting a new URL

## Security & Privacy

- Only upload images you have rights to use
- Don't upload sensitive personal information
- Images uploaded to public services are publicly accessible
- Consider privacy before uploading personal photos

## Alternative: Using Your Own Domain

If you have a website or domain, you can:
1. Upload images to your web hosting
2. Use the direct URLs from your domain
3. Example: `https://yourdomain.com/images/photo.jpg`

This gives you full control over the images but requires technical knowledge of web hosting.
