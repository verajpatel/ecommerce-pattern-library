## Project Information

This is a project that spans from the beginning of the semester to the end, which is 15 weeks. Throughout those 15 weeks, the designer's task is to create a pattern library for a e-commerce website that sells a certain demographic of items online. It can range from anything from figurines to bubbles. You will begin by figuring out what your brand and what you want to sell, as well as wire framing the looks of the website. After that, through the weeks, you will be building your pieces of the website, bit by bit each week.

## About Eggheads

Eggheads is a company that sells many different eggs. Many of these eggs can be used for many things, such as cooking, breeding purposes, or because you want a pet. Many rare and amazing eggs could be sold online, ranging from a chicken, to a dinosaur of your own choosing.

Before Eggheads became the Eggheads many people know of, it was previously called Yolk for Folk, which started up in 1974 as a black market/small secret shop for eggs alike. The original owner of the company, Alexander E. White, wanted to share the discovery of eggs with the entire world, so he created this company to spread the world of eggs.

## Installation

The pattern library is a Jekyll & Patternbot based application, so it requires certain programs to be installed for the pattern library to function. Ruby is one of those programs that is installed.

[*☛ Follow these instructions to get Ruby & Bundler installed*](https://learn-the-web.algonquindesign.ca/courses/web-dev-4/install-more-developer-tools/)

## Initialize Ruby & Bundler
1. Begin by forking and cloning the "ecommerce-pattern-library" repository from the website.
2. After forking the repository, begin by creating a file called ".ruby-version", adding just the numbers "2.6.2"
3. Navigate to the correct folder in Terminal. Use GitHub Desktop’s `Repository > Open in Terminal` command to open the repository's Terminal page.
4. Type the following command `bundle init`

## Gemfile
1. Once you return to your repository, there is a file called Gemfile.
2. Add the following code to your Gemfile before installing Jekyll & Patternbot:
  gem: "jekyll"

  group: :jekyll_plugins do
  gem "jekyll_patternbot"
  end

## Installing Jekyll & Patternbot

1. Navigate to the correct folder in Terminal. Use GitHub Desktop’s `Repository > Open in Terminal` command.
2. Type the following command `bundle install`
3. Configure Jekyll by using Patternbot by creating a config.yml with the following code:

  permalink: pretty;
  theme: "jekyll_patternbot"

---

## Starting the server

The pattern library is a Jekyll & Patternbot based application that requires a running Terminal instance.

1. Navigate to the correct folder in Terminal. Use GitHub Desktop’s `Repository > Open in Termal` command.
2. Type the following command: `bundle exec jekyll serve`
3. View the functional website at: [http://localhost:4000](http://localhost:4000)
4. View the pattern library at: [http://localhost:4000/pattern-library/](http://localhost:4000/pattern-library/)

To view the website on Netlify, you can visit the website domain at: [https://thirsty-shockley-543bcd.netlify.com/pattern-library/#brand] (https://thirsty-shockley-543bcd.netlify.com/pattern-library/#brand)

##Copyright Notice

The website is used for learning purposes only, instead of creating an actual website. All images and icons used, alongside the logo, belong to the appropriate users. Forking and cloning the website, and changing the code for your own purposes is prohibited.
