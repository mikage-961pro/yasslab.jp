---
layout: plain
lang:   ja
---

<section class="mainVisual">
  <div class="jumbotron">
    <picture>
      <source media="(min-width: 600px)" srcset="/img/cover-photo.jpg">
      <img src="/img/cover-photo-mobile.jpg" alt="Having a Good Life with OpenSource">
    </picture>

    <div class="logo-catch">
      <img src="/img/icons/yasslab.svg" width="270" alt="YassLab Logo">
      <h1>Having a Good Life with OpenSource ;)</h1>
    </div>
  </div>
</section>

<section class="catchCopy entry_content" id="vision">
  <div class="container">
    <div class="row">
      <div class="col-12">
        <h2><a href="#vision">新しいサービスを、Ruby で</a></h2>
        <p class="text-md-center">オープンソースソフトウェアやコミュニティへの還元を大切にしつつ、<br class="ignore-sp">事業としても共に成長できる、そんなビジネスに関わり続けている会社です。</p>
      </div>
    </div>
  </div>
</section>

<section class="products entry_content" id="products">
  <div class="container">
    <div class="row">
      <div class="col-12">
        <h3 style="line-height: 2.0em;"><a href="#products">《継続的翻訳/組版システム》</a><br>
	  Web 開発の学びを Ruby で支える</h3>

        <div class="row">
          <div class="col-md-4 offset-md-1">
            <a href="https://railstutorial.jp/" target="_blank"><img src="/img/logos/rails-tutorial.png"
                                                                     alt="Ruby on Rails チュートリアル"
                                                                     class="books"></a>
            <a href="https://railstutorial.jp/" target="_blank">
              <button class="btn btn-ruby">初級・中級者向け</button>
            </a>
            <a href="https://railstutorial.jp/" target="_blank"><h4>Railsチュートリアル</h4></a>
            <p>SNS の開発を題材にした大型チュートリアル。Web サービスの開発から公開までの流れを実例を通して学べます。<a href="https://railstutorial.jp/#screencast">解説動画</a>や<a href="https://railstutorial.jp/business">法人向けサービス</a>も提供。</p>
          </div>
          <div class="col-md-4 offset-md-2">
            <a href="https://railsguides.jp/" target="_blank">
              <img src="/img/logos/rails-guides.gif" alt="Ruby on Rails ガイド" class="books">
            </a>
            <a href="https://railsguides.jp/" target="_blank">
              <button class="btn btn-ruby">上級者向け</button>
            </a>
            <a href="https://railsguides.jp/" target="_blank"><h4>Railsガイド</h4></a>
            <p>Ruby on Rails 公式の大型リファレンスガイド。Rails の各機能を体系的に学び、Web 開発の生産性を高めたいときに。<a href="https://railsguides.jp/pro">全文検索サービス</a>も提供。</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="service entry_content" id="service">
  <div class="container">
    <div class="row">
      <div class="col-12">
        <h3 style="line-height: 2.0em;"><a href="#service" style="color: white;">《月額制の Ruby/Rails 開発支援》</a><br>
		開発事業を月単位でサポートします</h3>
        <div class="row mb-5">
          <div class="col-4">
            <figure id="ruby">
              <img src="/img/icons/ruby-pale.png" width="80%" alt="Ruby logo" />
               <figcaption>Ruby / Rails</figcaption>
            </figure>
          </div>
          <div class="col-4">
            <figure id="cloud">
              <img src="/img/icons/cloud-pale.png" width="80%" alt="cloud icon" />
              <figcaption>Heroku / AWS</figcaption>
            </figure>
          </div>
          <div class="col-4">
            <figure id="agile">
              <img src="/img/icons/agile-pale.png" width="80%" alt="Agile Development image" />
              <figcaption>Agile Development</figcaption>
            </figure>
          </div>
        </div><!--//row-->
      </div><!--//col-->
    </div><!--//row-->

   <div class="row">
      <div class="col-md-6">
        <div class="developmentSupport__more text-center">
            <a href="/ja/agile" class="btn btn-primary btn-block mt-2">詳細を見る</a>
          </div>
        </div><!--//col-->
        <div class="col-md-6">
        <div class="developmentSupport__more text-center">
            <a href="/ja/works" class="btn btn-primary btn-block mt-2">過去の実績を見る</a>
          </div>
        </div><!--//col-->
    </div><!--//row-->

  </div><!--//container-->
</section>

<section class="aboutVisual entry_content" id="remote">
  <div class="container">
    <div class="row">
      <div class="col-12">
        <h2><a href="#remote">沖縄
		×
		東京</a></h2>
        <p class="text-md-center h5">YassLab 社はソフトウェアエンジニアのリモートチームです。<br class="ignore-sp">フルタイム・パートタイム・複業、様々な関わり方があります。</p>
      </div><!--//col-->
    </div><!--//row-->
  </div><!--//container-->
</section>

<section class="okinawaMember" id="okinawa" style="margin-top: 50px;">
  <div class="container">
    <div class="row">
      <div class="col-12">
        <h3><a href="#okinawa">沖縄メンバー</a></h3>
        <div class="row">
          {% include member.html username='hanachin_'  link_to='twitter'
	           caption='<a href="http://ruby.okinawa/">Okinawa.rb</a>によく出没する。<a href="https://www.ipa.go.jp/jinzai/mitou/portal_index.html">未踏</a>クリエータ' %}
          {% include member.html username='himajin315' link_to='twitter'
             caption='プロの手相占い師兼エンジニア。<a href="https://ie.u-ryukyu.ac.jp/enpit/">enPiT</a>講師' %}
          {% include member.html username='nanophate'  link_to='twitter'
             caption='<a href="https://sechack365.nict.go.jp/">SecHack365</a> 採択者。バイリンガル、写真家' %}
          {% include member.html username='AnaTofuZ'   link_to='twitter'
             caption='Perlが好きなエンジニア。<a href="https://ie.u-ryukyu.ac.jp/%E5%AD%A6%E7%A7%91%E7%B4%B9%E4%BB%8B/%E7%A0%94%E7%A9%B6%E5%AE%A4%E7%B4%B9%E4%BB%8B/%E4%B8%A6%E5%88%97%E7%A0%94%E7%A9%B6%E5%AE%A4%EF%BC%88%E6%B2%B3%E9%87%8E%E7%A0%94%EF%BC%89/">並列研 (河野研)</a>' %}
          {% include member.html username='aokabin_' link_to='twitter'
             caption='<a href="https://www.ryukyu-frogs.com/">Ryukyufrogs</a>5期生のエンジニア。沖縄高専卒' %}
          {% include member.html username='naopontan' link_to='twitter'
             caption='Railsエンジニア。<a href="http://ruby.okinawa/okrk02/">沖縄Ruby会議</a>運営チーム' %}
        </div>
      </div>
    </div>
  </div>
</section>

<section class="tokyoMember" id="tokyo">
  <div class="container">
    <div class="row">
      <div class="col-12">
        <h3 class="mt-5"><a href="#tokyo">東京メンバー</a></h3>
        <div class="row">
	  {% include member.html username='yasulab'   link_to='twitter'
	  caption='IPA認定<a href="https://www.ipa.go.jp/jinzai/mitou/kinkyou/creator.html">未踏スーパークリエータ</a>。代表取締役' %}
	  {% include member.html username='nalabjp'   link_to='twitter'
	  caption='Railsエンジニア。スノーボードと沖縄が好き' %}

	  {% include member.html username='hachi8833' link_to='twitter'
	  caption='<a href="https://techracho.bpsinc.jp/">TechRacho</a>ライター。翻訳家、Go言語が好き' %}
	  {% include member.html username='shishi4tw' link_to='twitter'
	  caption='プログラマー。 <a href="https://twitter.com/hashtag/shinjukurb">Shinjuku.rb</a> 発起人' %}

	  {% include member.html username='crafter_gene' link_to='twitter'
	  caption='品質管理が得意。趣味は広くそこそこ深く' %}
	  {% include member.html username='Yuppyhappytoyou' link_to='twitter'
	  caption='楽しいこと大好き✌️
	  エンジニアママ😚 ' %}
	  
        </div>
	<div class="text-center pt-5" style="margin: 30px 0;">
          <a href="/ja/join-forces" class="btn btn-primary">
	    採用情報を見る
	  </a>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="sns">
  <div class="container">
    <div class="row gutter-10">
      <div class="col-6">
        <div class="card card__qiita">
          <div class="card__icon">
            <a href="https://qiita.com/organizations/yasslab"><img src="/img/logos/qiita.png" alt="YassLab organization in Qiita"></a>
          </div>
          <dl class="row">
            <dt class="col-md-6">投稿数</dt>
            <dd class="col-md-6">{% qiita_items %}</dd>
            <dt class="col-md-6">いいね</dt>
            <dd class="col-md-6">{% qiita_likes %}</dd>
          </dl>
        </div>
      </div>
      <div class="col-6">
        <div class="card card__github">
          <div class="card__icon">
            <a href="https://github.com/yasslab"><img src="/img/logos/github.png" alt="Yasslab organization in GitHub"></a>
          </div>
          <dl class="row">
            <dt class="col-md-6">リポジトリ数</dt>
            <dd id="github__repositories" class="col-md-6">65</dd>
            <dt class="col-md-6">スター数</dt>
            <dd id="github__stars" class="col-md-6">408</dd>
          </dl>
	  <div id="posts"></div>
        </div>
      </div>
    </div>
  </div>
</section>

<article>
  <div id="main_content_wrap" class="outer container" style="margin-top: 20px;">
    <section id="main_content" class="inner row justify-content-md-center pb-5 mb-5">
      <div class="col-12 col-md-9 entry_content text-center">
	{% include recent_posts.html %}
      </div>
    </section>
  </div>
</article>

<section class="community entry_content" id="community">
  <div class="container">
    <div class="row">
      <div class="col-12">
        <h2><a href="#community" style="color: white;">コミュニティ活動</a></h2>
        <p class="text-md-center">YassLab 社ではコミュニティを Hub とした様々な繋がりを大切にしています。<br class="ignore-sp">コミュニティの一員として、継続的にできることを積極的に提案します。</p>
        <div class="row">
          <div class="col-md-4">
            <figure>
              <a href="http://ruby.okinawa/" target="_blank">
                <img src="/img/logos/okinawarb.gif" alt="Okinawa Ruby User Group">
              </a>
              <figcaption><a href="http://ruby.okinawa/okrk02/">沖縄Ruby会議などの運営支援</a></figcaption>
            </figure>
          </div>
          <div class="col-md-4">
            <figure>
              <a href="/ja/doorkeeper/">
                <img src="/img/logos/doorkeeper.gif" alt="Doorkeeper スポンサーシップ">
              </a>
              <figcaption><a href="/ja/doorkeeper/">イベント管理サービス代の補助</a></figcaption>
            </figure>
          </div>
          <div class="col-md-4">
            <figure>
              <a href="https://coderdojo.jp/" target="_blank">
                <img src="/img/logos/coderdojo-japan.gif" alt="CoderDojo Japan - 子どものためのプログラミング道場">
              </a>
              <figcaption><a href="/ja/agile">Webサービスの開発支援</a></figcaption>
            </figure>
          </div>
        </div>

	<div class="text-center pt-5">
          <a href="/ja/about">
            <button class="btn btn-primary">会社概要を見る</button>
          </a>
        </div>

      </div>
    </div>
  </div>
</section>

<!--
<section class="partner">
  <div class="container">
    <div class="row">
      <div class="col-4">
        <a href="https://jr.mitou.org/" target="_blank">
          <img src="/img/logos/mitoujr.png" alt="未踏ジュニア">
        </a>
      </div>
      <div class="col-4">
        <a href="https://franliber.co.jp/" target="_blank">
          <img src="/img/logos/franliber.png" alt="FranLiber" class="bd-bk">
        </a>
      </div>
      <div class="col-4">
        <a href="https://railscp.com/" target="_blank">
          <img src="/img/logos/railscp.png" alt="（社）Rails技術者認定試験運営委員会" class="bd-bk">
        </a>
      </div>
    </div>
  </div>
</section>
-->

<section class="press" id="press">
  <div class="container">
    <div class="row">
      <div class="col-12">
        <h2><a href="#press">プレスリリース</a></h2>
          <ul>
            <li>
              <a href="https://www.members.co.jp/company/news/2018/0806_2.html" target="_blank">常駐型デジタルプロフェッショナルサービスのメンバーズキャリア、技術顧問体制を強化～新たに2名が技術顧問に就任、社員育成によるサービス向上を目指す～</a>
            </li>
            <li>
              <a href="https://prtimes.jp/main/html/rd/p/000000036.000015015.html" target="_blank">オンラインプログラミング学習のProgateが「Ruby on Rails チュートリアル」のコンテンツ提供でYassLabと提携</a>
            </li>
            <li><a href="https://prtimes.jp/main/html/rd/p/000000004.000021148.html" target="_blank">転職特化型Rubyプログラミングスクールの「ポテパンキャンプ」、Railsチュートリアルと業務提携しエンジニア創出を促す</a></li>
            <li><a href="https://www.value-press.com/pressrelease/190639" target="_blank">ShareWis、Ruby on Rails 5.1に対応したRailsチュートリアル [第4版] の動画講座を現役エンジニアによるQ&amp;A対応付きで提供開始</a></li>
            <li><a href="https://prtimes.jp/main/html/rd/p/000000013.000016641.html" target="_blank">プログラミングスクールの「DIVE INTO CODE」、Railsチュートリアルと公式提携した「DIC Railsチュートリアルコース」を発表</a></li>
          </ul>

      </div><!--//col-->
    </div><!--//row-->
  </div><!--//container-->
</section>

<div id="contact"></div>
