# Web Applications
I'm a quality engineer who loves merging my experience from both technical and commercial software roles to support teams in delivering high quality solutions.
Here, you'll find a few examples of Python/Javascript tools I created along the way to tackle business or testing challenges.

### mysslchecker.com

Retrieves and categorises SSL certificate data for a given list of websites. The list is stored in the user’s personal Google Drive and accessed via the Google Sheets API. Includes configurable email alerts.

{% include youtube.html id="AmvyUrkLVnk" %}
<br />

| Technologies Used                                                    |                                                                                           |
| -------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| Python, Heroku, Google Sheets API (v3), Redis, JavaScript, CSS, HTML | [GitHub](https://github.com/rintin-tim/mysslchecker) [App](https://mysslchecker.com/) |

### GetScreenshot

GetScreenshot takes screenshots for a list of URLs using multiple browsers and devices. It enhances Browserstack's native functionality by enabling users to bulk send a list of URLs which can be reviewed in a single custom slideshow.

{% include youtube.html id="A87HuONLpOo" %}
<br />

| Technologies Used                                                                          |                                                        |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------ |
| Python, Heroku, Browserstack screenshot API, PostgreSQL, Redis, JavaScript, HTML, CSS |  [GitHub](https://github.com/rintin-tim/get_screenshot/)|

# QA Tools

### Scripts to help with repetitive manual QA tasks

## Form printer

Print your current form data to a new browser tab before you submit it

<a href="https://github.com/rintin-tim/print_form" target="_blank"><img src="print-form.png" alt="print form example" width="640"></a>

| Technologies Used     |                                                      |
| --------------------- | ---------------------------------------------------- |
| JavaScript, HTML, CSS | [• GitHub](https://github.com/rintin-tim/print_form) |

## Domain toggle

Toggle between identical URL paths on two different domains - without manually and repetitively changing the URL in the browser.

This can be useful for comparing webpages across production and staging environments or across different regions.

_Example - switch between:_

- Test page: https://test.com/yellow-rubber-ducks
- Live page: https://live.com/yellow-rubber-ducks

| Technologies Used |                                                         |
| ----------------- | ------------------------------------------------------- |
| JavaScript        | [• GitHub](https://github.com/rintin-tim/domain_toggle) |
