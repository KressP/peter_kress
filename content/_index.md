---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        ### Saving Behavior, Homeownership, and the Terms of Credit
        <span style="color: grey;">Coauthor: Lea Fricke</span><br>
        **Summary:** We investigate the influence of the terms of credit on consumption, saving, and housing decisions of young households. To do so, we develop an incomplete-markets life-cycle model that features an endogenous borrowing price schedule. Incorporating a mortgage rate that increases with the loan-to-value ratio introduces a novel and strong savings incentive. Calibrating the model to German data, we find that our model with a flexible mortgage rate accurately replicates observed upfront savings and the age distribution of new homeowners. Comparisons with fixed-rate benchmarks point to the importance of incorporating such housing market realism and emphasize the impact of the terms of credit on upfront savings, housing choices, and investment dynamics. We identify differences in mortgage rates as a key source of heterogeneity in marginal propensities to consume non-durables.

        ### Transactional Data on Consumption Expenditures for Germany and Austria
         <span style="color: grey;">Coauthors: Winfried Koeniger, Jonas Lehmann</span><br>
        **Summary:** We present the transactional card expenditure data for Germany and Austria provided by Fable Data. We describe the data and explain how we construct the expenditure time series, which we then compare to existing information from external data sources. Our analysis shows how consumption expenditures have evolved during the recent crisis triggered by the pandemic, illustrating the advantages of the transactional data in terms of its granular, daily information on expenditures across items and locations.

        ### The Effect of Unconventional Fiscal Policy on Consumption - New Evidence based on Transaction Data
         <span style="color: grey;">Coauthor: Winfried Koeniger</span><br>
        **Summary:** We use transaction-level card expenditure data to estimate the effect of the temporary value-added tax (VAT) rate cut in Germany in the second half of 2020. We use card expenditures in Austria as control because no analogous VAT cut was implemented in Austria and spending of Austrian households provides a stable benchmark to compare spending of German households against. As predicted by consumption theory, we find that the temporary VAT cut increased the consumption growth rate more for durable goods, with a stronger effect close to the end of the cut. 
    design:
      columns: '1'
      css_style: "max-width: 1200px; margin: 0 auto;"
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!
        
        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
