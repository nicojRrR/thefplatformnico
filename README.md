# thefplatformnico<link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
import zipfile

# Correct way to create a zip file with the uploaded image
zip_file_path = "/mnt/data/theplatformnico_assets.zip"

# Create a zip file
with zipfile.ZipFile(zip_file_path, 'w') as zipf:
    zipf.write(image_path, arcname="image.png")

zip_file_path
<!-- Instagram-like logo -->
<img src="images/instagram-logo.png" alt="Instagram Logo" class="logo">

<!-- Home Icon -->
<img src="images/home-icon.png" alt="Home Icon" class="home-icon">

<!-- Profile Icon -->
<img src="images/profile-icon.png" alt="Profile Icon" class="profile-icon">
