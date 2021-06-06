<style>
html, body, div, span, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
abbr, address, cite, code,
del, dfn, em, img, ins, kbd, q, samp,
small, strong, sub, sup, var,
b, i,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, figcaption, figure,
footer, header, hgroup, menu, nav, section, summary,
time, mark, audio, video {
  margin:0;
  padding:0;
  border:0;
  outline:0;
  font-size:100%;
  vertical-align:baseline;
  background:transparent;
}

body {
  line-height:1;
}

article,aside,details,figcaption,figure,
footer,header,hgroup,menu,nav,section {
  display:block;
}

nav ul {
  list-style:none;
}

blockquote, q {
  quotes:none;
}

blockquote:before, blockquote:after,
q:before, q:after {
  content:'';
  content:none;
}

a {
  margin:0;
  padding:0;
  font-size:100%;
  vertical-align:baseline;
  background:transparent;
}

/* change colours to suit your needs */
ins {
  background-color:#ff9;
  color:#000;
  text-decoration:none;
}

/* change colours to suit your needs */
mark {
  background-color:#ff9;
  color:#000;
  font-style:italic;
  font-weight:bold;
}

del {
  text-decoration: line-through;
}

abbr[title], dfn[title] {
  border-bottom:1px dotted;
  cursor:help;
}

table {
  border-collapse:collapse;
  border-spacing:0;
}

/* change border colour to suit your needs */
hr {
  display:block;
  height:1px;
  border:0;
  border-top:1px solid #cccccc;
  margin:1em 0;
  padding:0;
}

input, select {
  vertical-align:middle;
}
</style>

<template>
  <div id="app">
    <CommonHeader></CommonHeader>
    <main>
      <div id="eyecatch">
        <p>estra</p>
      </div>
      <div id="about">
        <h2 class="section-title">about</h2>
        <div class="about-wrap">
          <div class="about-left">
            <img src="@/assets/img/bg1.jpg" alt="" />
          </div>
          <div class="about-right">
            <h3>estra inc.</h3>
            <p>
              私たちは、お客様の満足度を徹底的に追及することで、お客様・市場・時代のニーズを的確に捉え、事業の拡大と周辺ビジネスによる差別化、業界における圧倒的な地位の確立を図るべく積極的な事業活動を行っています。
            </p>
            <ol>
              <li>コーチング事業</li>
              <li>プログラミング事業</li>
              <li>SaaS事業</li>
            </ol>
          </div>
        </div>
      </div>
      <div id="business">
        <h2 class="section-title">service</h2>
        <div class="business-wrap">
          <div class="business-cat">
            <img src="@/assets/img/bg2.jpg" alt="" />
            <h3>ビジネスA</h3>
            <p>
              ビジネスの説明が入ります。ビジネスの説明が入ります。ビジネスの説明が入ります。ビジネスの説明が入ります。
            </p>
          </div>
          <div class="business-cat">
            <img src="@/assets/img/bg2.jpg" alt="" />
            <h3>ビジネスB</h3>
            <p>
              ビジネスの説明が入ります。ビジネスの説明が入ります。ビジネスの説明が入ります。ビジネスの説明が入ります。
            </p>
          </div>
          <div class="business-cat">
            <img src="@/assets/img/bg2.jpg" alt="" />
            <h3>ビジネスC</h3>
            <p>
              ビジネスの説明が入ります。ビジネスの説明が入ります。ビジネスの説明が入ります。ビジネスの説明が入ります。
            </p>
          </div>
        </div>
      </div>
      <div id="company">
        <h2 class="section-title">company</h2>
        <table class="contain">
          <tr>
            <th>会社名</th>
            <td>株式会社estra</td>
          </tr>
          <tr>
            <th>代表者名</th>
            <td>福場凜太郎</td>
          </tr>
          <tr>
            <th>本社所在地</th>
            <td>東京都渋谷区1-1</td>
          </tr>
          <tr>
            <th>従業員数</th>
            <td>100名</td>
          </tr>
          <tr>
            <th>電話番号</th>
            <td>0120-000-0000</td>
          </tr>
          <tr>
            <th>FAX</th>
            <td>0120-000-0000</td>
          </tr>
          <tr>
            <th>メールアドレス</th>
            <td>rintaro@estra.inc</td>
          </tr>
          <tr>
            <th>資本金</th>
            <td>1000万円</td>
          </tr>
          <tr>
            <th>事業内容</th>
            <td>コーチング</td>
          </tr>
        </table>
      </div>
      <div id="contact">
        <h2 class="section-title">contact</h2>
        <form class="form" method="post">
          <div>
            <label for="name">Name:</label>
            <input type="text" id="name" name="user_name" />
          </div>
          <div>
            <label for="mail">E-mail:</label>
            <input type="email" id="mail" name="user_mail" />
          </div>
          <div>
            <label for="tell">Tell:</label>
            <input type="tel" id="tel" name="user_tel" />
          </div>
          <div>
            <label for="msg">Message:</label>
            <textarea id="msg" name="user_message"></textarea>
          </div>
          <div class="button-submit">
            <button class="button" type="submit">Button</button>
          </div>
        </form>
      </div>
    </main>
    <CommonFooter></CommonFooter>
  </div>
</template>

<script>
import CommonHeader from "./components/CommonHeader.vue";
import CommonFooter from "./components/CommonFooter.vue";
export default {
  components: {
    CommonHeader,
    CommonFooter
  }
};
</script>

<style>
html, body, div, span, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
abbr, address, cite, code,
del, dfn, em, img, ins, kbd, q, samp,
small, strong, sub, sup, var,
b, i,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, figcaption, figure,
footer, header, hgroup, menu, nav, section, summary,
time, mark, audio, video {
  margin:0;
  padding:0;
  border:0;
  outline:0;
  font-size:100%;
  vertical-align:baseline;
  background:transparent;
}

body {
  line-height:1;
}

article,aside,details,figcaption,figure,
footer,header,hgroup,menu,nav,section {
  display:block;
}

nav ul {
  list-style:none;
}

blockquote, q {
  quotes:none;
}

blockquote:before, blockquote:after,
q:before, q:after {
  content:'';
  content:none;
}

a {
  margin:0;
  padding:0;
  font-size:100%;
  vertical-align:baseline;
  background:transparent;
}

/* change colours to suit your needs */
ins {
  background-color:#ff9;
  color:#000;
  text-decoration:none;
}

/* change colours to suit your needs */
mark {
  background-color:#ff9;
  color:#000;
  font-style:italic;
  font-weight:bold;
}

del {
  text-decoration: line-through;
}

abbr[title], dfn[title] {
  border-bottom:1px dotted;
  cursor:help;
}

table {
  border-collapse:collapse;
  border-spacing:0;
}

/* change border colour to suit your needs */
hr {
  display:block;
  height:1px;
  border:0;
  border-top:1px solid #cccccc;
  margin:1em 0;
  padding:0;
}

input, select {
  vertical-align:middle;
}
</style>
