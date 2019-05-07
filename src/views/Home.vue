<template>
  <div class="home">
    <div class="content">
      <div class="professional-detail show-boder">
        <div class="title">
          professional details
        </div>
        <div class="picture">
          <img src="@/assets/IMG_0515.png" />
        </div>

        <div class="info">
          <table>
            <tbody>
              <tr>
                <td class="label">
                  Name
                </td>
                <td class="value">
                  Manh Vu
                </td>
              </tr>
              <tr>
                <td class="label">
                  Age
                </td>
                <td class="value">
                  {{ age }}
                </td>
              </tr>
              <tr>
                <td class="label">
                  Location
                </td>
                <td class="value">
                  Ho Chi Minh, VN
                </td>
              </tr>
              <tr>
                <td class="label">
                  Experience
                </td>
                <td class="value">{{ yearExp }} years</td>
              </tr>
              <tr>
                <td class="label">
                  Degree
                </td>
                <td class="value">
                  Bachelor
                </td>
              </tr>
              <tr>
                <td class="label">
                  Phone
                </td>
                <td class="value">
                  <a :href="`tel:${phone}`">{{ phone }}</a>
                </td>
              </tr>
              <tr>
                <td class="label">
                  Email
                </td>
                <td class="value">
                  <a :href="`mailto:${email}`">{{ email }}</a>
                </td>
              </tr>
            </tbody>
          </table>
        </div>
      </div>

      <div class="about-me">
        <div class="title">
          About me
        </div>
        <p>
          I’m a web developer. I have about {{ yearExp }} years of experience.
          My strong point is responsibility. I focus on delivering hight quality
          and produtivity. Sometimes, I have to trade-off them in specific
          preriod of production. By years, I was knowledgeable different
          projects, frameworks as well as libraries, which allow to make
          development faster. For example in server side, Serverless using AWS
          as provider which I used to deploy Graphql written in Node js.
          Front-end side I can use React js, Vue js, Angurla. Of course I’m good
          in HTML and CSS.
        </p>
        <p>
          I am also concentrating on designing product that meets client needs
          and is easy to add new features. After read you job description, I
          really like your teck-stack. I think I fit with them. I hope you make
          a chance for an interview to discuss further.
        </p>

        <div class="title">
          Education
        </div>
        <p>
          2008 - 2012 Bachelor credit of Electronics and Telecommunication
          Technologies, Vietnam National University, Hanoi. GPA 2.73/4 Thesis
          grade 9.4/10 Toeic 680 (certificated by IIG) Specialized in Automation
          and Control
        </p>

        <div class="title">
          Technical skills
        </div>
        <p>
          Programming language Java; Javascript Back-end technologies Spring
          framework (Spring Core, Spring MVC, Spring Security, Spring Data),
          Hibernate, Redis, Elasticsearch, Tomcat 7 Front-end technologies
          HTML5, Javascript, CSS, React JS Database MySQL, Dynamo-DB Tools
          IntelliJ, Git Operating system Window, Linux, Mac OS
        </p>

        <div class="title">
          working experience
        </div>
        <p>
          August 2017 - Now Lecle Vietnam Company, Web Developer, Paragon
          building, 3 St. Nguyen Luong Bang, W. Tan Phu , 7 District, Ho Chi
          Minh. I lead team with 6 members, and successfully deploy 2 projects:
          Bemypet, and whosewallet. Project: Bemypet website for pet adoption;
          WhoseWallet; nanum { Build front-end using Webpack React Js, Sass,
          Html5 { Build back end using graphql, dynamo-db, serverless - aws
          lambda. October 2015 - July 2017 Clearway Solution Company, Developer,
          B96 St. Bach Dang, W. 2 , Tan Binh District, Ho Chi Minh. I worked in
          project Gts, Cpq and Aleka: design data base table; implement good
          perfoment back-end API (Java, Spring framework): well organize,
          maintainable and extendable code; implement front end (javascript,
          html, css). Project: GTS & CPQ { GTS: Develop web site that helps
          management furniture factory { CPQ: Develop e-commerce selling
          furniture using Broadleaf framework http://www.broadleafcommerce.com {
          Aleka(exchanges of car for rent https://aleka.vn/: Develop website
          that allow customer to search car. I take part in all phases of
          development. Technologies were: React JS, Bootstrap, Thymeleaf, Spring
          Boot, Elasticsearch, Postgres April 2015 - October 2015 MService
          Company, Senior Java Developer, 40 Hoang Viet, Tan Binh District, Ho
          Chi Minh. I worked in project MMV2 - build app MOMO version 2
          (https://momo.vn/ ) Project: MMV2 { Layout mobile app screen using
          Xamarin Framework, and implement business logic process { Develop and
          implement back-end API (using Vertx Framework). 1/54 Nguyen Thai Son,
          W. 3, Go Vap District – Ho Chi Minh City H 0973 623 390 • B
          manh.vv.htth@gmail.com 2/4 August 2014 - April 2015 FPT Software Ho
          Chi Minh, Dev 2, Saigon Hi-Tech Park, Ho Chi Minh. Working as a
          backend developer in a project team of about 50 people. Required to
          understand clearly the requirement of the assigned development tasks
          from team lead and make sure those tasks are accomplished with high
          productivity and quality. Project: AcTvila - a company selling video
          online in Japan (August 2014 - April 2015) { Work in Back-End team
          with about 10 members. { My main task is developing APIs for business
          requirement on Admin (Manage Genre, Group, Content, Download meta data
          OEM partner and OEM User) and Front-End page (Maintain Genre List)
          April 2013 - July 2014 BTM Global Consulting, Engineer I, Quang Trung
          Software City, Ho Chi Minh. Handle development tasks depending on
          different phases, time and the need of software project development
          cycles. Project: NEXcom, Decker (Retailer using Oracle retail
          software) POS, BO, CO - oracle retail software which were used by
          Retail Company for their business (April 2013 - July 2014) { I work in
          development team with about 6 to 12 members { My main task is
          implement new function for POS application November 2012 - March 2013
          Tessi Asia, Java Developer, Nguyen Trong Loi Street, Tan Binh
          District, Ho Chi Minh. Project: Tessi documents services September
          2012 - November 2012 Freelancer, Java, Ho Chi Minh. Project: Web Film
          and Video { Develop function of manage genre Miscellaneous May 2012 -
          October 2012 Texas Instrument MCU Contest 2012, North region. Texas
          Instrument MCU Contest were conducted by Texas Instrument. This event
          was for helping student familiar with Texas chip. I participated
          contest with project Monitoring Conversation which was got in Northern
          Region final. 2010 - 2011 Scientific Research for Student 2010-2011,
          University of Engineering and Technology. My report has title Security
          in building using autonomous robot. My team have two members, I and my
          classmate. Our report was get good appreciation from Council Reviewer
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
  data() {
    const now = new Date();
    const yearNow = now.getFullYear();
    return {
      age: yearNow - 1990,
      yearExp: yearNow - 2013,
      phone: "+84973623390",
      email: "manh.vv.htth@gmail.com"
    };
  }
};
</script>

<style lang="scss">
$pl: 15px;
$bg: #f7f4f8;

body {
  background-color: $bg;
}

.content {
  display: flex;
  align-items: flex-start;
  width: 960px;
  min-height: 100vh;
  margin: 0 auto;

  table {
    width: 100%;
  }

  .title {
    height: 2em;
    text-align: left;
    padding-left: $pl;
    text-transform: uppercase;
    font-weight: bold;
    line-height: 2em;

    border-bottom: 2px solid $bg;
  }

  .professional-detail {
    flex: 3 1;
    background-color: white;
    margin-right: 20px;
    padding-bottom: 2em;

    .picture {
      background-color: #ddccab;
      margin-bottom: 1.6em;
      img {
        width: 100%;
      }
    }

    .info {
      padding: 0 $pl;
      font-size: small;

      .label {
        text-transform: uppercase;
        font-weight: bold;
        text-align: left;
      }
      .value {
        text-align: left;
      }
    }
  }
  .about-me {
    flex: 7 1;
    background-color: white;
    padding-bottom: 2em;

    p {
      text-align: left;
      padding: 0 $pl;
    }
  }
}
</style>
