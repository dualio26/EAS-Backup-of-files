<template>
  <div>
    <client-only placeholder="loading...">
      <Header />
    </client-only>
    <div class="banner">
      <div class="scrollable">
        <img src="../images/Landscape.svg" alt="Landscape" />
      </div>
      <div class="SubTitle">
        <p class="title">Think Global Act Local</p>
        <p class="buttons">
          <NuxtLink to="carbonfootprint"
            ><button style="background-color: #bcd8ee; color: #4a4a4a">
              <h3>Carbon Footprint</h3>
            </button></NuxtLink
          ><NuxtLink to="carboncredits"
            ><button style="background-color: #86c886; color: #f5f3ee">
              <h3>Carbon Credits</h3>
            </button></NuxtLink
          >
        </p>
        <p class="heading2">
          Supporting you in the
          <span style="color: #89b7db">transition</span> to a
          <span style="color: #86c886">sustainable</span> future.
        </p>
      </div>
    </div>

    <div class="CaseStudy1">
      <div class="Cap1">
        <p>Filler Content</p>
      </div>
      <div class="Capsule1">
        <div class="content">
          <div>
            <img src="../images/Summit.png" alt="WAOSumImage" />
          </div>
          <div>
            <h3>Case Study</h3>
            <h1 class="CSTitles">WAO Summit</h1>
            <p class="CSText">
              Wao is a charitable trust dedicated to educating, inspiring and
              enabling New Zealand communities to accelerate beyond
              sustainability towards a thriving future. Based in the Southern
              Lakes region, WAO look to inspire, educate and enable communities
              to look towards the opportunities created by this transition and
              help to shape a future that looks towards not just a sustainable
              future, but one where people give back more than they take.
            </p>
            <a href="waosum.html" class="CSLinks">Read this case study</a>
          </div>
        </div>
      </div>
    </div>

    <div class="CaseStudy2">
      <img src="../images/WorldBank.png" alt="WorldBankImg" />
      <h3>Case Study</h3>
      <h1 class="CSTitles2">
        Ski Areas Association<br />
        of New Zealand
      </h1>
      <p class="CSText2">
        Made up of representatives from commercial and club ski fields across
        New Zealand, SAANZ’s sustainability group, approached EAS well aware of
        the impacts that climate change can have on the future of the ski and
        snow-sports industry. An industry so intrinsically linked to weather,
        nature and the environment.
      </p>
      <a href="waosum.html" class="CSLinks">Read this case study</a>
    </div>

    <div class="CaseStudy3">
      <img src="../images/WAIWanaka2.png" alt="WorldBankImg" />
      <h3>Case Study</h3>
      <h1 class="CSTitles">WAI Wānaka</h1>
      <p class="CSText3">
        WAI Wānaka’s vision is to safeguard and enhance water quality, ecosystem
        function and biodiversity within the Upper Clutha basin. <br /><br />
        Moving at pace, WAI Wānaka aims to connect the many individuals,
        community groups, iwi, landowners and businesses undertaking positive
        work towards building healthy ecosystems and supporting community
        wellbeing.
      </p>
      <a href="waosum.html" class="CSLinks">Read this case study</a>
    </div>

    <div class="ClientList">
      <h1 style="margin-bottom: 5%">Our Clients</h1>
      <div class="grid-container">
        <div class="grid-item">
          <img src="../images/nz.png" alt="" style="width: 100%" />
        </div>
        <div class="grid-item">
          <img src="../images/WAO-02.svg" alt="" style="width: 50%" />
        </div>
        <div class="grid-item">
          <img src="../images/201801_gfoi_logo.png" alt="" />
        </div>
        <div class="grid-item">
          <img src="../images/index.png" alt="" style="width: 40%" />
        </div>
        <div class="grid-item">
          <img
            src="../images/ipcc_altlogo_short_rgb.png"
            alt=""
            style="width: 60%"
          />
        </div>
        <div class="grid-item">
          <img src="../images/worldbankLogo.png" alt="" />
        </div>
        <div class="grid-item">
          <img src="../images/wai-wanaka-logo.png" alt="" style="width: 60%" />
        </div>
        <div class="grid-item">
          <img
            src="../images/fao_logo_3lines_en1.png"
            alt=""
            style="width: 100%"
          />
        </div>
      </div>
    </div>

    <!--This is the div for the services Carousel-->
    <div class="Services"></div>

    <client-only>
      <div class="Publications">
        <h1>Publications</h1>
        <div class="cards">
          <div id="C1" class="CColumn">
            <a href="https://www.reddcompass.org/search-the-mgd">
              <div class="card1">
                <h2 class="CTitles">GFOI Methods and Guidance Document</h2>
                <div class="container">
                  <p>
                    Integration of remote-sensing and ground-based observations
                    for estimation of emissions and removals of greenhouse gases
                    in forests.
                  </p>
                </div>
              </div>
            </a>

            <a href="https://doi.org/10.1016/j.rse.2019.111492">
              <div class="card3">
                <h2 class="CTitles">
                  Mitigating the effects of omission errors on area and area
                  change estimates
                </h2>
                <div class="container">
                  <p>Remote Sensing of Environment</p>
                </div>
              </div>
            </a>
          </div>

          <div id="C2" class="CColumn">
            <a
              href="https://www.ipcc-nggip.iges.or.jp/public/2019rf/index.html"
            >
              <div id="card2" class="card2">
                <h2 class="CTitles">IPCC 2019 Refinement</h2>
                <div class="container">
                  <p>
                    2019 Refinement to the 2006 IPCC Guidelines for National
                    Greenhouse Gas Inventories
                  </p>
                </div>
              </div>
            </a>

            <a href="https://doi.org/10.3390/rs13112172">
              <div id="card4" class="card4">
                <h2 class="CTitles">
                  Capacity Development for Use of Remote Sensing for REDD+ MRV
                </h2>
                <div class="container">
                  <p>
                    Using Online and Offline Activities: Impacts and Lessons
                    Learned.
                  </p>
                </div>
              </div>
            </a>
          </div>
        </div>
      </div>
    </client-only>

    <!--Div for the insight carousel-->
    <div class="Insights"></div>

    <!--Div fo the Who we are carousel-->
    <div class="WWA"></div>

    <div class="InTouch">
      <h1>Who we are</h1>
    </div>

    <div class="GIT">
      <h2 class="CTitles">Get in touch to see how we can help you</h2>
      <form action="mailto:eamongreen59@gmail.com">
        <input id="fname" type="text" name="fname" placeholder="Name" />
        <input
          id="lname"
          type="text"
          name="email"
          placeholder="Email"
        /><br /><br />
        <select id="" name="" placeholder="Subject">
          <option value="" disabled selected>Subject</option>
          <option value="TechProb">Technical Issue</option>
        </select>
        <input
          id="fname"
          type="text"
          name="phone"
          placeholder="Phone"
        /><br /><br />
        <textarea
          id="w3review"
          name="w3review"
          rows="4"
          cols="50"
          placeholder="Message"
          style="color: #f5f3ee"
        >
        </textarea>
        <br /><br />
        <input type="submit" value="Submit" style="border-style: none" />
      </form>
    </div>

    <footer>
      <a href="#Top">
        <i class="fas fa-home fa-2x"></i>
      </a>
      <ul class="flist">
        <li>
          <p><a href="tel:0211234123">Phone:</a> 021 1234 123</p>
        </li>

        <li>
          <p>
            <a href="mailto:info@enviroaccounts.com">Email:</a>
            info@enviroaccounts.com
          </p>
        </li>
      </ul>
      <ul class="ficons">
        <li>
          <a href="mailto:info@enviroaccounts.com"
            ><i class="fas fa-envelope fa-lg"></i></a
          >&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;: info@enviroaccounts.com
        </li>
        <li>
          <a href="tel:0211234123"><i class="fas fa-phone fa-sm"></i></a
          >&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;: 021 1234 123
        </li>
      </ul>
      <p class="fotcrit">
        © Environmental Accounting Services 2021 | Website by Adam Hall Design
      </p>
    </footer>
  </div>
</template>

<script>
export default {
  mounted: () => {
    setInterval(function () {
      const height = document.querySelector('#C1').offsetHeight
      // window.console.log(height + ' column 1 height')
      const x = height + 'px'
      document.getElementById('C2').style.height = x
      const c2h = document.querySelector('#card2').offsetHeight
      const c4h = document.querySelector('#card4')
      const style = getComputedStyle(c4h)

      const mb = parseInt(style.marginBottom)
      // window.console.log(c2h + ' card 2 height')
      const y = height - c2h - mb * 2
      // window.console.log(y)
      document.getElementById('card4').style.height = y + 'px'
    }, 250)
  },
}
</script>
