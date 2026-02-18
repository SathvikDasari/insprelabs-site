# 🚀 Deploying Changes to the Live Website

The InspireLabs website is automatically deployed using GitHub Actions.

Any change merged into the main branch will rebuild and update the live
site.

------------------------------------------------------------------------

# 🔒 Important Rule

Do NOT push directly to main.

All changes must go through a branch and Pull Request (PR).

------------------------------------------------------------------------

# 🌿 Deployment Workflow

## 1️⃣ Update Local Repository

git checkout main git pull

------------------------------------------------------------------------

## 2️⃣ Create a New Branch

git checkout -b your-branch-name

Example: git checkout -b update-contact-page

------------------------------------------------------------------------

## 3️⃣ Make Changes and Test

hugo server

Verify everything works correctly.

------------------------------------------------------------------------

## 4️⃣ Commit Changes

git add . git commit -m "Short description of changes"

------------------------------------------------------------------------

## 5️⃣ Push Branch

git push origin your-branch-name

------------------------------------------------------------------------

## 6️⃣ Create Pull Request

1.  Go to GitHub
2.  Click "Compare & pull request"
3.  Add description
4.  Submit PR

------------------------------------------------------------------------

## 7️⃣ Merge After Review

After approval: - Merge into main - GitHub builds automatically - Site
deploys in 1--2 minutes

------------------------------------------------------------------------

# 🔎 Verify Deployment

1.  Check GitHub → Actions for green checkmark
2.  Visit https://inspirelabs.org
3.  Confirm changes are live

------------------------------------------------------------------------

# 🏁 Summary

git checkout main git pull git checkout -b new-branch (edit + test) git
add . git commit -m "message" git push origin new-branch Create Pull
Request Merge after review
