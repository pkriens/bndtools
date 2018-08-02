---
---

<style>
    .fi-burst-new { font-size: 48px; color: #F04124; }
</style>

<div class="hero">
    <h1>Install Bndtools</h1>
    <p>Bndtools currently supports all versions of Eclipse from <b>Luna (4.4)</b>* up to and including <b>Oxygen (4.7)</b>. <small>*Bndtools m2e (Maven) support requires Eclipse Mars (4.5) or later.</small></p>

    <div data-alert class="alert-box info radius">
        <div class="row">
            <div class="large-1 columns">
              <i class="fi-burst-new"></i>
            </div>
            <div class="large-11 columns">
              <h4><a href="https://github.com/bndtools/bndtools/wiki/Changes-in-3.5.0" target="_blank">Bndtools 3.5.0 Released! Check out the changes &raquo;</a></h4>
            </div>
        </div>
    </div>

    <!--<p>&nbsp;</p>-->

    <div class="row">
        <div class="large-6 columns">
            <h2>Via Marketplace</h2>
            <p>The recommended way to install Bndtools.</p>
            <p><a class="button primary" href="#marketplace">View details &raquo;</a></p>
        </div>

        <div class="large-6 columns">
            <h2>Via Update Site</h2>
            <p>Use the update site if your Eclipse installation does not include the Marketplace client.</p>
            <p><a class="button primary" href="#update-site">View details &raquo;</a></p>
            
            <p>Install a <a href="#nonstandard_versions">Development Snapshot or an Older Version &raquo;</a></p>
        </div>
    </div>
</div>

<hr/>

<section id="marketplace">
    <div class="row">
        <h1>Eclipse Marketplace</h1>
    </div>

    <div class="row">
        <div class="small-12 columns">
            <p>
                Drag and drop this install button onto your running Eclipse: <a href="http://marketplace.eclipse.org/marketplace-client-intro?mpc_install=1220" class="drag" title="Drag to your running Eclipse workspace. NB: Requires Eclipse Marketplace Client"><img class="img-responsive" src="https://marketplace.eclipse.org/sites/all/themes/solstice/public/images/marketplace/btn-install.png" alt="Drag to your running Eclipse workspace. NB: Requires Eclipse Marketplace Client"/></a>
            </p>
        </div>
    </div>

    <div class="row">
        <div class="small-12 columns text-center"><h2>&#8230; OR &#8230;</h2></div>
    </div>
    <hr/>
    
    <div class="row">
        <div class="small-1 columns"><h2>1.</h2></div>
        <div class="small-4 columns"><img src="/images/installation/mplace01.png" class="thumbnail"/></div>
        <div class="small-7 columns">
            <p>From the Help menu select Eclipse Marketplace.</p>
            <p>If this is the first time you have used the marketplace, you <em>may*</em> be asked to choose a solutions catalog. Select <strong>Eclipse Marketplace</strong> and click next.</p>
        </div>
    </div>
    <hr/>

    <div class="row">
        <div class="small-1 columns"><h2>2.</h2></div>
        <div class="small-4 columns"><img src="/images/installation/mplace02.png" class="thumbnail"/></div>
        <div class="small-7 columns">
            <p>Type <code>bnd</code> into the search field and click Go.</p>
            <p>Click "Install" next to the Bndtools entry.</p>
        </div>
    </div>
    <hr/>
    <div class="row">
        <div class="small-1 columns"><h2>3.</h2></div>
        <div class="small-4 columns"><img src="/images/installation/mplace03.png" class="thumbnail"/></div>
        <div class="small-7 columns">
            <p>Drive the wizard to completion, following the on-screen instructions.</p>
        </div>
    </div>
</section>

<hr/>

<section id="update-site">
    <div class="row">
        <h1>Update Site</h1>
    </div>

    <div class="row">
        <div class="small-1 columns"><h2>1.</h2></div>
        <div class="small-4 columns"><img src="/images/installation/updatesite01.png" class="thumbnail"/></div>
        <div class="small-7 columns">
            <p>From the Help menu select Install New Software...</p>
            <p>When the dialog opens, click the "Add..." button near the top-right.</p>
        </div>
    </div>
    <hr/>
    <div class="row">
        <div class="small-1 columns"><h2>2.</h2></div>
        <div class="small-4 columns"><img src="/images/installation/updatesite02.png" class="thumbnail"/></div>
        <div class="small-7 columns">
            <p>In the Name field enter Bndtools. In the Location field enter one of the the following URLs and click OK. For the latest stable release:</p>
            <pre>https://dl.bintray.com/bndtools/bndtools/latest/</pre>

        <p>For other versions, see the <a href="#nonstandard_versions">table below</a>.</p>

        </div>
    </div>
    <hr/>
    <div class="row">
        <div class="small-1 columns"><h2>3.</h2></div>
        <div class="small-4 columns"><img src="/images/installation/updatesite03.png" class="thumbnail"/></div>
        <div class="small-7 columns">
            <p>Ensure that Bndtools is selected from the "Work with" drop-down selector. Then place a check next to Bndtools in the Software list and click Next.</p>
        </div>
    </div>
    <hr/>
    <div class="row">
        <div class="small-1 columns"><h2>4.</h2></div>
        <div class="small-4 columns"><img src="/images/installation/updatesite04.png" class="thumbnail"/></div>
        <div class="small-7 columns">
            <p>Click Next again to confirm the installation operation.</p>
            <p>Drive the wizard to completion, following the on-screen instructions.</p>
        </div>
    </div>
</section>

<hr/>

<section id="nonstandard_versions">
    <div class="row">
        <h1>Installing Development or Older Versions</h1>
    </div>

    <p>The Eclipse Marketplace can only be used to install the current stable version of Bndtools.
    If you want to install a development milestone or an old version, you
    must use the <a href="#update-site">update site method</a> as shown above. The following
    update site URLs are available:</p>

    <table class="table table-striped">
        <thead><th>Version</th><th>Update Site URL</th></thead>

        <tbody>
            <tr>
                <td>Development Snapshot</td>
                <td><strong>NB</strong>: This build tracks the very latest version of the code, and is likely to be unstable or contain experimental features. <br/> <code>https://bndtools.ci.cloudbees.com/job/bndtools.master/lastSuccessfulBuild/artifact/build/generated/p2/</code></td>
            </tr>
            <tr>
                <td><strong>Current Release 3.5.0</strong> (29 Sept 2017)</td>
                <td><code>https://dl.bintray.com/bndtools/bndtools/3.5.0/</code></td>
            </tr>
            <tr>
                <td>Release 3.4.0 (25 Jul 2017)</td>
                <td><code>https://dl.bintray.com/bndtools/bndtools/3.4.0/</code></td>
            </tr>
            <tr>
                <td>Release 3.3.0 (17 Sep 2016)</td>
                <td><code>https://dl.bintray.com/bndtools/bndtools/3.3.0/</code></td>
            </tr>
            <tr>
                <td>Release 3.2.0 (16 May 2016)</td>
                <td><code>https://dl.bintray.com/bndtools/bndtools/3.2.0/</code></td>
            </tr>
            <tr>
                <td>Release 3.1.1 (22 Jan 2016)</td>
                <td><code>https://dl.bintray.com/bndtools/bndtools/3.1.1/</code></td>
            </tr>
            <tr>
                <td>Release 3.1.0 (18 Dec 2015)</td>
                <td><code>https://dl.bintray.com/bndtools/bndtools/3.1.0/</code></td>
            </tr>
            <tr>
                <td>Release 3.0.0 (10 Sep 2015)</td>
                <td><code>https://bndtools-updates.s3.amazonaws.com/3.0.0.REL/</code></td>
            </tr>
            <tr>
                <td>Release 2.4.0 (3 Nov 2014)</td>
                <td><code>https://bndtools-updates.s3.amazonaws.com/2.4.0.REL/</code></td>
            </tr>
            <tr>
                <td>Release 2.3.0 (10 May 2014)</td>
                <td><code>https://bndtools-updates.s3.amazonaws.com/2.3.0.REL/</code></td>
            </tr>
            <tr>
                <td>Release 2.2.2 (25 Jan 2013)</td>
                <td><code>https://bndtools-updates.s3.amazonaws.com/2.2.2.REL/</code></td>
            </tr>
        </tbody>
    </table>


    <p>Note that bugfixes will not generally be supplied for old versions.</p>

</section>
