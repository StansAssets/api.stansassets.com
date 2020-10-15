
# Stan's Assets API website
This project is used to maintain the docfx project for the [Web Stan's Assets API](https://api.stansassets.com/)

### How to use
* Website is located under the `docs` folder.
* Make sure docfx is installed. (for example if you are using  mac [Homebrew](https://formulae.brew.sh/formula/docfx) run `brew install docfx`). Or check **DocFX** section for more details.
* To regenerate the website content, remove files under the `docs` folder, run `docfx docfx-project/docfx.json` 
* If you want to preview created site locally, run `docfx docfx-project/docfx.json -t statictoc`
* Make sure you have the following repos on the same level
* * Plugins
* * com.stansassets.foundation

## Example
Here is a good example of how to connect a new package to the documentation website. There were only 2 simple steps to add `com.stansassets.build` documentation generation. See the examples below:
* [Commit to the current repo](https://github.com/StansAssets/api.stansassets.com/commit/96e6d4935db0e45a067ca7920e2ae5ae8b6403b2)
* [Commit it the com.stansassets.build repo](https://github.com/StansAssets/com.stansassets.build/commit/cf50320f1035d8057e469207b3e00312fc268033)


### DocFx
* [Getting Started Guide](https://dotnet.github.io/docfx/tutorial/docfx_getting_started.html)
* [Themes](https://dotnet.github.io/docfx/templates-and-plugins/templates-dashboard.html)

Other nice looking static websites powered by DocFx
* Testify [Git repo](https://github.com/wekempf/testify) | [Website](http://wekempf.github.io/testify/)

### Github pages
Static site will be hoster from the `master` branch /  `master` branch docs folder / `gh-pages` branch (whatever you prefer in the settings.)

*Subdomain set up:*
* Repo Options - set custom subdomain to `api.stansassets.com`
* Add domain `CNAME` record: `api / stansassets.github.io`


*Tutorials / Info*
* [How to Use a GoDaddy Custom Subdomain with GitHub Pages Hosting](https://medium.com/@SeloSlav/how-to-use-a-godaddy-custom-subdomain-with-github-pages-hosting-fbac17f36f9d)
* [Using custom domain for GitHub pages](https://medium.com/@hossainkhan/using-custom-domain-for-github-pages-86b303d3918a)

* [Does GitHub Pages Support HTTPS for www and @ subdomains?](https://github.community/t5/GitHub-Pages/Does-GitHub-Pages-Support-HTTPS-for-www-and-subdomains/td-p/7116)
