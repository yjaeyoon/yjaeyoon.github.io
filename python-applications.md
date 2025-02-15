---
layout: page
title: "Python Code - Applied"
---
Python is a powerful tool for **accounting research** and **data analytics**. On this webpage, I share some python code to demonstrate **how I use Python for accounting research** with a focus on the following topics: <br>
* How to get access to XBRL from SEC EDGAR;<br>
* How to get data from WRDS;<br>
* How to handle data using Pandas and Numpy;<br>
* How to visualize data, either static or dynamic.<br>

---

All code files are stored <a href="https://github.com/jaeyoonyu/jaeyoonyu.github.io/blob/main/_code" target="_blank">here</a>. Check anything you're interested in:


* [How to get access to XBRL data from SEC EDGAR using Python.](https://nbviewer.org/github/jaeyoonyu/jaeyoonyu.github.io/blob/main/_code/xbrl-extract-info.ipynb)<br/>
* How to get access to PCAOB AP filings.<br/>
    * [Download AP filings](https://nbviewer.org/github/jaeyoonyu/jaeyoonyu.github.io/blob/main/_code/pcaob-auditorsearch-download.ipynb).<br/>
    * [Cleanse AP filings](https://nbviewer.org/github/jaeyoonyu/jaeyoonyu.github.io/blob/main/_code/pcaob-auditorsearch-cleanse.ipynb).<br/>    
* [How to get access to WRDS using Python.](https://nbviewer.org/github/jaeyoonyu/jaeyoonyu.github.io/blob/main/_code/wrds-intro.ipynb)<br/>
    * Compustat
        * Company.
        * [funda (10-K)](https://nbviewer.org/github/jaeyoonyu/jaeyoonyu.github.io/blob/main/_code/wrds-download-compustat.ipynb).
        * [fundq (10-Q)](https://nbviewer.org/github/jaeyoonyu/jaeyoonyu.github.io/blob/main/_code/wrds-download-compustat-fundq.ipynb).
        * [Segment files](https://nbviewer.org/github/jaeyoonyu/jaeyoonyu.github.io/blob/main/_code/compustat-preview-segment-data.ipynb).
    * CRSP
        * Monthly files: [msf](https://nbviewer.org/github/jaeyoonyu/jaeyoonyu.github.io/blob/main/_code/wrds-download-crsp-msf.ipynb); [msi](https://nbviewer.org/github/jaeyoonyu/jaeyoonyu.github.io/blob/main/_code/wrds-download-crsp-msi.ipynb); mse.
        * Daily files: dsf; dsi; dse; [dsedelist](https://nbviewer.org/github/jaeyoonyu/jaeyoonyu.github.io/blob/main/_code/wrds-download-crsp-dsedelist.ipynb).
        * CRSP-Compustat Merged (CCM).
        * CRSP-IBES Link.
    * IBES
        * ID files: 
            [id](https://nbviewer.org/github/jaeyoonyu/jaeyoonyu.github.io/blob/main/_code/wrds-download-ibes-id.ipynb); 
            [idsum](https://nbviewer.org/github/jaeyoonyu/jaeyoonyu.github.io/blob/main/_code/wrds-download-ibes-idsum.ipynb).
        * [surpsumu (surprise, unadjusted)](https://nbviewer.org/github/jaeyoonyu/jaeyoonyu.github.io/blob/main/_code/wrds-download-ibes-surpsumu.ipynb).
        * [det_guidance (Guidance)](https://nbviewer.org/github/jaeyoonyu/jaeyoonyu.github.io/blob/main/_code/wrds-download-ibes-det_guidance.ipynb).        
    * Audit Analytics
        * [Client info (auditcblock)](https://nbviewer.org/github/jaeyoonyu/jaeyoonyu.github.io/blob/main/_code/wrds-download-AuditAnalytics-auditcblock.ipynb)
        * Panel sets: [Audit Opinions](https://nbviewer.org/github/jaeyoonyu/jaeyoonyu.github.io/blob/main/_code/wrds-download-AuditAnalytics-auditopin.ipynb); [SOX404](https://nbviewer.org/github/jaeyoonyu/jaeyoonyu.github.io/blob/main/_code/wrds-download-AuditAnalytics-sox404.ipynb); Sox302; Accelerated filers.
        * Event sets:
            [CAMs](https://nbviewer.org/github/jaeyoonyu/jaeyoonyu.github.io/blob/main/_code/wrds-download-AuditAnalytics-CAM.ipynb);
            [IPOs](https://nbviewer.org/github/jaeyoonyu/jaeyoonyu.github.io/blob/main/_code/wrds-download-AuditAnalytics-ipo.ipynb);
            [Bankruptcy](https://nbviewer.org/github/jaeyoonyu/jaeyoonyu.github.io/blob/main/_code/wrds-download-AuditAnalytics-bankrupt.ipynb); 
            [Data breach](https://nbviewer.org/github/jaeyoonyu/jaeyoonyu.github.io/blob/main/_code/wrds-download-AuditAnalytics-cyber-security.ipynb); 
            Restatements; 
            Late filings; 
            Auditor changes;
            Comment letters.
    * BoardEx
        * [board chars](https://nbviewer.org/github/jaeyoonyu/jaeyoonyu.github.io/blob/main/_code/wrds-download-boardex-bdchars.ipynb).
* Financial data for one company: [UBER](https://nbviewer.org/github/jaeyoonyu/jaeyoonyu.github.io/blob/main/_code/check-one-company-uber.ipynb).
* Can we get <b>IPO years from Compustat</b>? Yes we can. Check [the distribution.](https://nbviewer.org/github/jaeyoonyu/jaeyoonyu.github.io/blob/main/_code/Compustat-ipodate.ipynb)<br/>
* Yearly distribution of <b>loss firms</b>: More than half are loss firms in 2020.<br>
    * [Version 1. Using matplotlib after aggregating data method](https://nbviewer.org/github/jaeyoonyu/jaeyoonyu.github.io/blob/main/_code/compustat-loss-firm-distribution-v1.ipynb). <br>
    * [Version 2. Using seaborn and raw data method](https://nbviewer.org/github/jaeyoonyu/jaeyoonyu.github.io/blob/main/_code/compustat-loss-firm-distribution-v2.ipynb). <br>
* [SEC filing distribution](https://nbviewer.org/github/jaeyoonyu/jaeyoonyu.github.io/blob/main/_code/SEC_filings_dist.ipynb) provided by SEC EDGAR.<br/>
* Does the <b>earning kink at zero</b> still exist? Maybe not any more. [Check the distribution.](https://nbviewer.org/github/jaeyoonyu/jaeyoonyu.github.io/blob/main/_code/is-there-kink-around-zero.ipynb)<br/>
* [Earnings announcement date distribution](https://nbviewer.org/github/jaeyoonyu/jaeyoonyu.github.io/blob/main/_code/earnings-ann-date-dist.ipynb) using IBES.<br/>
* <b>Seaborn</b> allows to visualize data with multiple dimensions: [scatterplot of firm size, profitability, and auditor size.](https://nbviewer.org/github/jaeyoonyu/jaeyoonyu.github.io/blob/main/_code/sctterplot-ROA-size-Big4.ipynb)<br/>
* <b>Plotly for animated visualization</b><br>
    * [Auditors' client distribution](https://raw.githack.com/jaeyoonyu/jaeyoonyu.github.io/main/_code/audit-analytics-client-distribution.html).<br/>
    * Dynamic scatter plot: [ROA & Sales over time](https://raw.githack.com/jaeyoonyu/jaeyoonyu.github.io/main/_code/compustat-bubble-plot-animation.html).<br>
* WRDS processes some BoardEx datasets and provides <b>the processed ones</b> as well as raw ones. <b>Are they reliable?</b> See [the figure at the end of this code](https://nbviewer.org/github/jaeyoonyu/jaeyoonyu.github.io/blob/main/_code/wrds-download-boardex-bdchars.ipynb).<br>
 
<!-- To render HTML and get a link:
https://raw.githack.com/
-->

<!-- To render .ipynb with dynamic plots:
Use nbviewer
-->
