import React, { useState } from 'react';
import { Menu, X, BookOpen, Users, Star, MessageCircle, ChevronRight, Award, Megaphone, Quote, Heart, PlayCircle, Info } from 'lucide-react';

// --- モックデータ ---

const FEATURED_ARTICLES = [
  {
    id: 'f1',
    vol: 'Vol.32',
    date: '2026.02',
    title: '特集「感動」は偶然じゃない！お客様の心を動かす『感動の方程式』を解き明かす',
    content: `
      「感動」って一体どうやって生まれるのでしょうか？実は、感動には明確なメカニズムがあります。
      お客様がサービスを受けた時に抱く感情は、「事前期待値」と「実感値」のギャップで決まります。
      
      ・実感値 ＜ 事前期待値 = 「不満」
      ・実感値 ＝ 事前期待値 = 「満足」
      ・実感値 ＞ 事前期待値 = 「感動！」
      
      つまり、感動を生むためには、お客様がお店に来る前に持っている期待を、ほんの少しでも「上回る」ことが必要です。
      
      【明日からできる！夢チャレ流「感動への3ステップ」】
      1. お客様の「背中」にある言葉を拾う（主役以外を見る、否定の裏を読む）
      2. 「あなただけ」の特別扱いを入れる（名前で呼び続ける、雑談を武器にする）
      3. 数字だけでなく「ストーリー」も共有する（ナイスプレーのシェア、TTP：徹底的にパクる）
    `,
    imagePlaceholder: ''
  },
  {
    id: 'f2',
    vol: 'Vol.24',
    date: '2025.06',
    title: '40周年の幕開け！夢の実現へ！郡会長の想いを伺いました！',
    content: `
      40年も経ったのか･･･、もう一瞬やったな･･･という感覚です。24歳でこの事業を始めて以来、本当に一瞬だったと思います。
      この先の10年間をどう生きるか。やっぱり、本来やりたかったこと、心の底から成し遂げたいと思っていたことに、本気で、全身全霊で取り組みたいと思うんです。
      
      今期40期の1年間において成し遂げたいことは、『全社全事業全部門全店全拠点・達成』をしたい！
      完璧な計画のもと、完璧な実績を作り上げる。未来の京ろまんグループを創造するためにも、利益・収益を確実に確保する。今、私はそのことを誰よりも強く、そして真剣に考えています。
    `,
    imagePlaceholder: ''
  },
  {
    id: 'f3',
    vol: 'Vol.28',
    date: '2025.10',
    title: '号外!! 万博社員旅行、大成功に終わる！アンケート結果公開',
    content: `
      9月16日に開催された、京ろまんグループ40周年記念・社員旅行『大阪万博』。熱中症多発の混乱もありつつも、大盛況のうちに幕を閉じました。
      
      【参加されて良かった点（抜粋）】
      ・普段話せない他店舗の方と話せたり、ゆっくり話せたのが良かった。
      ・なかなかこんな機会ないので行けるきっかけになってありがたかった。
      ・スタッフの仲間意識ができた。
      ・万博ならではの、異国の雰囲気を味わうことができた。
      
      次回行きたい場所としては、USJ、ディズニー、温泉、京都などが多く挙げられました！
    `,
    imagePlaceholder: ''
  }
];

const PERSONS = [
  {
    id: 'p1',
    vol: 'Vol.25',
    name: '田中 里佳 委員長',
    company: 'チャレンジ！夢・感動！委員会',
    quote: '夢を語り、夢に挑み、夢を創造する',
    details: '明るく、ポジティブ真剣シンキングでいることです。ネガティブなことでも常にポジティブ変換するようにしています。今期は皆と一緒に目標を追いかけ、達成したいと思っています。'
  },
  {
    id: 'p2',
    vol: 'Vol.25',
    name: '木村 由梨子 さん',
    company: '株式会社京ろまんGHD きもの事業部 営業企画室',
    quote: '10年後のビジョンに向け、少しずつでも着実に',
    details: 'モチベーションを上げるために推しの写真や動画を見ます。営業スタッフさんが目標達成できる環境をサポートすること、それが私の役割です。いつまでも着物を着て楽しむことが夢です。'
  },
  {
    id: 'p3',
    vol: 'Vol.26',
    name: '藤田 一慧 店長',
    company: '株式会社ファーストステージ 寝屋川店',
    quote: 'ファーストステージを日本一にする！',
    details: '人を成長させられるリーダーを目指しています。自分一人の力ではなく、たくさんのメンバーの力を繋いでお客様に「感動」をお届けできるようなチーム作りに努めます！'
  },
  {
    id: 'p4',
    vol: 'Vol.26',
    name: '小川 七海 さん',
    company: '株式会社京ろまんGHD わぷらす奈良',
    quote: '着物を通じて人と人の心をつなぐ',
    details: '海外のお客様と英語でコミュニケーションを取りながら、着物を通じて日本文化を伝えられることに喜びを感じています。もっとお客様に喜んでもらえる存在になりたいです。'
  },
  {
    id: 'p5',
    vol: 'Vol.27',
    name: '親川 卓史 エリア長',
    company: '株式会社京ろまんGHD 第二エリア長',
    quote: '全員一丸になり達成できた喜び',
    details: '40期より2店舗兼任となり責任の重さを感じています。事業部の売上、利益を出し念願の「きもの事業部創社」に貢献したいです。'
  },
  {
    id: 'p6',
    vol: 'Vol.27',
    name: '源根 花歩 さん',
    company: '株式会社ファーストステージ 中山寺店',
    quote: '沢山チャレンジして、苦手意識を好きに変える',
    details: 'ヘアメイク・着付け・カメラ・内覧と、オールマイティにこなせるスタッフになることが夢です。お客様からもスタッフからも信頼される関係性を作り続けます。'
  },
  {
    id: 'p7',
    vol: '2026.3',
    name: '長田 竹織 室長',
    company: '株式会社京ろまんGHD きもの事業部 営業企画室',
    quote: '営業企画と学院運営の両面からアプローチ',
    details: '集客や業務効率化の仕組みを導入し、新規客の獲得や売上向上の課題を解決します。写真すべてが、ガッツポーズでした！'
  },
  {
    id: 'p8',
    vol: '2026.3',
    name: '堂山 貴世子 副店長',
    company: '株式会社京ろまんGHD きもの事業部 桜井店',
    quote: '信頼できる仲間と着物愛に溢れるお店を',
    details: '仕事では、信頼できる仲間と「着物愛に溢れるお店」を作り、楽しく結果を出したい！私生活では、4人の子供を早く自立させ、しっかり稼いで自由な人生を大いに謳歌したい！'
  }
];

const VISIONS_2026 = [
  {
    role: '京ろまんグループ 代表',
    name: '郡 史朗 会長',
    vision: '各会社・事業、各店舗の売上パーフェクト達成の月を作る！全員がやるべきことをやれる組織に進化させる！',
    challenge: '健康のために毎日30分歩く、チャットGPT・GoogleGeminiのフル活用'
  },
  {
    role: '株式会社百花',
    name: '平野 俊輔 社長',
    vision: '2027年は私の干支ですので、必ず百花を復活させます。今期は黒字で締め、来期は全店黒字で予算達成をさせます。',
    challenge: '1年間に最低50本以上の映画を鑑賞すること、週2回のジムでの筋トレ'
  },
  {
    role: '株式会社京ろまん',
    name: '竹内 哲郎 常務',
    vision: 'キモノ市場の価値観を変えたい！伝統や技術を守りながら、提供する価値を変える！',
    challenge: '現体重から20%オフにチャレンジ！'
  },
  {
    role: '株式会社ファーストステージ',
    name: '近藤 陽子 社長',
    vision: '40期ファーストステージの年間目標達成を必ずやり切る。振袖の店外催事で全会場売上1000万円達成目標。',
    challenge: '23時就寝'
  }
];

const COMMITTEE_MEMBERS = [
  { name: '田中 りか', dept: '百花マネジメント部', image: '' },
  { name: '荒瀬 博', dept: 'きもの事業部 ならファミリー店', isNew: true, image: '' },
  { name: '藤田 一慧', dept: 'ファーストステージ 寝屋川店', image: '' },
  { name: '白崎 憲司', dept: 'KyoDo', image: '' }
];

const WORDS = [
  { month: '3月 (2020年)', text: '期待を超えてからが本当の仕事' },
  { month: '2月 (2015年)' },
  { month: '1月 (2002年)' },
  { month: '12月' },
  { month: '11月 (2019年)' },
  { month: '10月 (2018年)' },
  { month: '9月 (2019年)' },
  { month: '8月 (2015年)' },
  { month: '7月 (2018年)' },
  { month: '6月 (2022年)' }
];

// --- コンポーネント ---

const App = () => {
  const [activeTab, setActiveTab] = useState('home');
  const [isMobileMenuOpen, setIsMobileMenuOpen] = useState(false);
  const [selectedArticle, setSelectedArticle] = useState(null);
  const [selectedPerson, setSelectedPerson] = useState(null);

  const navItems = [
    { id: 'home', label: 'トップページ', icon: <BookOpen className="w-5 h-5" /> },
    { id: 'about', label: '夢チャレ委員会とは', icon: <Heart className="w-5 h-5" /> },
    { id: 'features', label: '特集記事', icon: <Star className="w-5 h-5" /> },
    { id: 'persons', label: 'ネクスト！パーソン', icon: <Users className="w-5 h-5" /> },
    { id: 'visions', label: '役員の抱負 (2026)', icon: <Megaphone className="w-5 h-5" /> },
    { id: 'words', label: '郡会長の言魂', icon: <Quote className="w-5 h-5" /> },
  ];

  const handleNavClick = (id) => {
    setActiveTab(id);
    setSelectedArticle(null);
    setSelectedPerson(null);
    setIsMobileMenuOpen(false);
  };

  const renderContent = () => {
    // 特集記事の詳細表示
    if (selectedArticle) {
      return (
        <div className="animate-fadeIn max-w-4xl mx-auto bg-white p-8 rounded-2xl shadow-sm border border-pink-100">
          <button 
            onClick={() => setSelectedArticle(null)}
            className="flex items-center text-gray-500 hover:text-pink-600 mb-6 transition-colors"
          >
            <ChevronRight className="w-5 h-5 rotate-180 mr-1" />
            一覧に戻る
          </button>
          <div className="flex items-center gap-3 mb-4">
            <span className="bg-pink-500 text-white text-xs font-bold px-3 py-1 tracking-wider rounded-full">{selectedArticle.vol}</span>
            <span className="text-gray-500 text-sm">{selectedArticle.date}</span>
          </div>
          <h1 className="text-3xl font-bold mb-6 text-gray-900 leading-tight">{selectedArticle.title}</h1>
          
          <div className="w-full h-64 bg-pink-50 rounded-xl flex items-center justify-center mb-8 border border-pink-100">
            <span className="text-pink-300 font-medium">{selectedArticle.imagePlaceholder}</span>
          </div>
          
          <div className="prose max-w-none text-gray-700 leading-relaxed whitespace-pre-line">
            {selectedArticle.content}
          </div>
        </div>
      );
    }

    // ネクストパーソンの詳細表示（1人1ページ）
    if (selectedPerson) {
      return (
        <div className="animate-fadeIn max-w-4xl mx-auto bg-white p-8 md:p-12 rounded-2xl shadow-sm border border-pink-100">
          <button 
            onClick={() => setSelectedPerson(null)}
            className="flex items-center text-gray-500 hover:text-pink-600 mb-8 transition-colors"
          >
            <ChevronRight className="w-5 h-5 rotate-180 mr-1" />
            一覧に戻る
          </button>
          
          <div className="flex flex-col md:flex-row gap-10 items-center md:items-start">
            <div className="w-48 h-48 md:w-72 md:h-72 bg-gradient-to-br from-pink-100 to-orange-100 rounded-full flex-shrink-0 flex items-center justify-center border-4 border-white shadow-lg overflow-hidden relative">
              <Users className="text-pink-300 w-24 h-24 absolute opacity-20" />
              <span className="text-pink-400 font-bold relative z-10">[Photo]</span>
            </div>
            
            <div className="flex-1 text-center md:text-left">
              <div className="flex items-center justify-center md:justify-start gap-3 mb-4">
                <span className="bg-pink-500 text-white text-xs font-bold px-4 py-1.5 tracking-wider rounded-full shadow-sm">{selectedPerson.vol}</span>
              </div>
              <p className="text-sm font-bold text-pink-500 mb-2">{selectedPerson.company}</p>
              <h1 className="text-3xl md:text-4xl font-black mb-8 text-gray-900 border-b-2 border-pink-100 pb-4">{selectedPerson.name}</h1>
              
              <div className="bg-pink-50/80 p-6 md:p-8 rounded-2xl border border-pink-100 relative shadow-inner">
                <Quote className="absolute top-4 left-4 text-pink-200 w-10 h-10 opacity-60" />
                <p className="font-bold text-xl md:text-2xl text-pink-800 mb-6 text-center md:text-left relative z-10 md:pl-8 leading-relaxed">
                  &quot;{selectedPerson.quote}&quot;
                </p>
                <div className="text-gray-700 leading-relaxed relative z-10 md:pl-8 whitespace-pre-line">
                  {selectedPerson.details}
                </div>
              </div>
            </div>
          </div>
        </div>
      );
    }

    switch (activeTab) {
      case 'home':
        return (
          <div className="space-y-12 animate-fadeIn">
            {/* Hero Section */}
            <div className="relative bg-gradient-to-r from-pink-400 to-orange-400 text-white rounded-3xl overflow-hidden shadow-xl">
              <div className="absolute inset-0 opacity-20 bg-[url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyMCIgaGVpZ2h0PSIyMCI+CjxjaXJjbGUgY3g9IjIiIGN5PSIyIiByPSIyIiBmaWxsPSIjZmZmZmZmIiAvPgo8L3N2Zz4=')]"></div>
              <div className="relative p-10 md:p-16 text-center">
                <div className="inline-flex items-center justify-center bg-white/20 backdrop-blur-sm px-4 py-1.5 rounded-full mb-6">
                  <Heart className="w-4 h-4 mr-2 text-white fill-white" />
                  <span className="text-sm md:text-base font-bold tracking-[0.1em] text-white">チャレンジ！夢・感動委員会</span>
                </div>
                <h1 className="text-5xl md:text-7xl font-black mb-6 tracking-tight drop-shadow-md">ネクストステージ</h1>
                <p className="text-lg md:text-xl font-medium tracking-widest text-white/90 drop-shadow">
                  京ろまんグループの夢と感動の創造を！ <br className="md:hidden" /> Go! Next STAGE!
                </p>
              </div>
            </div>

            {/* Latest Features */}
            <div>
              <div className="flex items-center justify-between mb-6 border-b-2 border-pink-500 pb-2">
                <h3 className="text-2xl font-bold text-gray-900 flex items-center gap-2">
                  <Star className="text-yellow-400 fill-yellow-400" /> 注目の特集記事
                </h3>
                <button onClick={() => setActiveTab('features')} className="text-sm font-bold text-pink-600 hover:text-pink-700 hover:underline">すべて見る</button>
              </div>
              <div className="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
                {FEATURED_ARTICLES.slice(0, 3).map(article => (
                  <div 
                    key={article.id} 
                    onClick={() => setSelectedArticle(article)}
                    className="bg-white rounded-2xl shadow-sm border border-pink-100 overflow-hidden cursor-pointer hover:shadow-md hover:border-pink-300 transition-all group"
                  >
                    <div className="h-40 bg-pink-50 flex items-center justify-center border-b border-pink-100 group-hover:bg-pink-100 transition-colors">
                      <span className="text-xs text-pink-300">{article.imagePlaceholder}</span>
                    </div>
                    <div className="p-5">
                      <div className="flex items-center gap-2 mb-3">
                        <span className="bg-pink-500 text-white text-xs font-bold px-2.5 py-1 rounded-full">{article.vol}</span>
                      </div>
                      <h4 className="text-lg font-bold text-gray-900 line-clamp-2 group-hover:text-pink-600 transition-colors">{article.title}</h4>
                    </div>
                  </div>
                ))}
              </div>
            </div>

            {/* Pick Up Person */}
            <div>
              <div className="flex items-center justify-between mb-6 border-b-2 border-pink-500 pb-2">
                <h3 className="text-2xl font-bold text-gray-900 flex items-center gap-2">
                  <Users className="text-orange-400" /> ネクスト！パーソン
                </h3>
                <button onClick={() => setActiveTab('persons')} className="text-sm font-bold text-pink-600 hover:text-pink-700 hover:underline">すべて見る</button>
              </div>
              <div className="grid md:grid-cols-2 gap-6">
                {PERSONS.slice().reverse().slice(0, 4).map(person => (
                  <div 
                    key={person.id} 
                    onClick={() => setSelectedPerson(person)}
                    className="bg-white p-6 rounded-2xl shadow-sm border border-pink-100 flex gap-4 items-center hover:shadow-md hover:border-pink-300 transition-all cursor-pointer group"
                  >
                    <div className="w-16 h-16 bg-gradient-to-br from-pink-100 to-orange-100 rounded-full flex-shrink-0 flex items-center justify-center overflow-hidden border-2 border-white shadow-sm">
                      <Users className="text-pink-400 w-8 h-8 group-hover:scale-110 transition-transform" />
                    </div>
                    <div className="flex-1">
                      <span className="text-xs font-bold text-pink-500 mb-1 block">{person.vol} | {person.company}</span>
                      <h4 className="text-lg font-bold text-gray-900 group-hover:text-pink-600 transition-colors">{person.name}</h4>
                    </div>
                    <ChevronRight className="w-5 h-5 text-gray-300 group-hover:text-pink-500 transition-colors" />
                  </div>
                ))}
              </div>
            </div>

            {/* Others / News */}
            <div>
              <div className="flex items-center justify-between mb-6 border-b-2 border-pink-500 pb-2">
                <h3 className="text-2xl font-bold text-gray-900 flex items-center gap-2">
                  <PlayCircle className="text-pink-500" /> 今月のお知らせ
                </h3>
              </div>
              <div className="grid md:grid-cols-2 gap-6">
                <div className="bg-white p-6 rounded-2xl shadow-sm border border-pink-100 flex gap-4 items-start hover:shadow-md transition-all">
                  <div className="w-16 h-16 bg-red-50 text-red-500 rounded-2xl flex-shrink-0 flex items-center justify-center border border-red-100">
                    <PlayCircle className="w-8 h-8" />
                  </div>
                  <div>
                    <h4 className="text-lg font-bold text-gray-900 mb-2">YouTube グループ社員が選ぶ！</h4>
                    <p className="text-sm text-gray-600 mb-2">「行ってよかった場所」をご紹介！奈良県はグルメの宝庫！中でも新大宮駅近くの「オオミヤバル」は店主さんも面白くてオススメ！</p>
                  </div>
                </div>
                <div className="bg-white p-6 rounded-2xl shadow-sm border border-pink-100 flex gap-4 items-start hover:shadow-md transition-all">
                  <div className="w-16 h-16 bg-blue-50 text-blue-500 rounded-2xl flex-shrink-0 flex items-center justify-center border border-blue-100">
                    <Award className="w-8 h-8" />
                  </div>
                  <div>
                    <h4 className="text-lg font-bold text-gray-900 mb-2">チャレンジ！資格取得</h4>
                    <p className="text-sm text-gray-600">感動を生み出し、夢を実現させるために必須な「ビジネス実務マナー検定」。今回は『対人関係 - 断りの言葉の柔らかい言い方』です。ぜひチャレンジを！</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        );

      case 'about':
        return (
          <div className="animate-fadeIn space-y-12">
            <div>
              <h2 className="text-3xl font-bold mb-8 border-b-4 border-pink-500 pb-2 inline-block">夢チャレ！委員会とは</h2>
              <div className="bg-white p-8 rounded-2xl shadow-sm border border-pink-100 text-center relative overflow-hidden">
                <div className="absolute -top-10 -right-10 text-pink-50 opacity-50">
                  <Heart className="w-48 h-48" />
                </div>
                <h3 className="text-2xl font-black text-pink-600 mb-6 relative z-10">夢を語り、夢に挑み、夢を創造する</h3>
                <p className="text-lg text-gray-700 leading-relaxed mb-6 relative z-10">
                  『チャレンジ！夢・感動委員会』は、未来を見据え、新たな価値を創造していく、<br className="hidden md:block"/>
                  京ろまんグループのプラットフォームとしての役割を果たしていきます。
                </p>
                <div className="bg-pink-50 rounded-xl p-6 inline-block text-left relative z-10">
                  <p className="font-bold text-gray-900 mb-2">それぞれの会社・事業、そして個人の</p>
                  <ul className="space-y-2 text-pink-700 font-medium">
                    <li className="flex items-center"><Star className="w-4 h-4 mr-2" /> 『チャレンジ！』を応援してます！</li>
                    <li className="flex items-center"><Star className="w-4 h-4 mr-2" /> 『夢』の実現を後押しします！</li>
                    <li className="flex items-center"><Star className="w-4 h-4 mr-2" /> 『感動』を創造し続ける原動力になります！</li>
                  </ul>
                </div>
              </div>
            </div>

            <div>
              <h3 className="text-2xl font-bold mb-6 flex items-center gap-2"><Users className="text-pink-500"/> 委員会メンバー</h3>
              <div className="grid grid-cols-2 md:grid-cols-4 gap-6">
                {COMMITTEE_MEMBERS.map((member, i) => (
                  <div key={i} className="bg-white p-6 rounded-2xl shadow-sm border border-pink-100 text-center relative hover:-translate-y-1 transition-transform">
                    {member.isNew && (
                      <span className="absolute -top-3 -right-3 bg-orange-500 text-white text-xs font-black px-3 py-1 rounded-full shadow-md transform rotate-12">NEW!</span>
                    )}
                    <div className="w-20 h-20 mx-auto bg-pink-50 rounded-full flex items-center justify-center mb-4 border-4 border-white shadow-sm overflow-hidden">
                      <span className="text-xs text-pink-300">{member.image}</span>
                    </div>
                    <h4 className="font-bold text-gray-900 mb-1">{member.name}</h4>
                    <p className="text-xs text-gray-500">{member.dept}</p>
                  </div>
                ))}
              </div>
            </div>

            <div className="bg-gradient-to-r from-orange-400 to-pink-500 p-8 rounded-2xl text-white text-center shadow-lg">
              <h3 className="text-2xl font-black mb-4">緊急!! 夢チャレ委員メンバー 大募集</h3>
              <p className="mb-4 font-medium opacity-90">グローバルマーケティング営業部、Gマネジメント本部・商品部・Draw 4...</p>
              <p className="text-xl font-bold bg-white text-pink-600 inline-block px-6 py-2 rounded-full shadow-sm">どなたか！お待ちしております！</p>
            </div>
          </div>
        );

      case 'features':
        return (
          <div className="animate-fadeIn">
            <h2 className="text-3xl font-bold mb-8 border-b-4 border-pink-500 pb-2 inline-block">特集記事アーカイブ</h2>
            <div className="space-y-6">
              {FEATURED_ARTICLES.map(article => (
                <div 
                  key={article.id}
                  onClick={() => setSelectedArticle(article)}
                  className="bg-white p-6 rounded-2xl shadow-sm border border-pink-100 cursor-pointer hover:shadow-md hover:border-pink-300 transition-all flex flex-col md:flex-row gap-6"
                >
                  <div className="w-full md:w-48 h-32 bg-pink-50 rounded-xl flex items-center justify-center flex-shrink-0 border border-pink-100">
                    <span className="text-xs text-pink-300 px-2 text-center">{article.imagePlaceholder}</span>
                  </div>
                  <div className="flex-1">
                    <div className="flex items-center gap-3 mb-2">
                      <span className="bg-pink-500 text-white text-xs font-bold px-3 py-1 rounded-full">{article.vol}</span>
                      <span className="text-gray-500 text-sm">{article.date}</span>
                    </div>
                    <h3 className="text-xl font-bold mb-3 text-gray-900">{article.title}</h3>
                    <p className="text-gray-600 line-clamp-2 text-sm">{article.content}</p>
                  </div>
                </div>
              ))}
            </div>
          </div>
        );

      case 'persons':
        return (
          <div className="animate-fadeIn">
            <h2 className="text-3xl font-bold mb-8 border-b-4 border-pink-500 pb-2 inline-block">ネクスト！パーソン</h2>
            <p className="text-gray-600 mb-8">働く社員にスポットライトを当て、困難に直面しながらも踏み出した「チャレンジ」、夢の実現に向けた取り組みを深掘りします。</p>
            <div className="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
              {PERSONS.slice().reverse().map(person => (
                <div 
                  key={person.id} 
                  onClick={() => setSelectedPerson(person)}
                  className="bg-white p-6 rounded-2xl shadow-sm border border-pink-100 hover:border-pink-400 hover:shadow-md transition-all cursor-pointer group"
                >
                  <div className="flex items-center justify-between mb-4">
                    <span className="bg-pink-50 text-pink-600 text-xs font-bold px-3 py-1 rounded-full">{person.vol}</span>
                    <Award className="text-orange-400 w-5 h-5 opacity-50 group-hover:opacity-100 transition-opacity" />
                  </div>
                  <div className="flex justify-center mb-6">
                     <div className="w-28 h-28 bg-gradient-to-br from-pink-100 to-orange-100 rounded-full flex items-center justify-center border-4 border-white shadow-sm overflow-hidden group-hover:scale-105 transition-transform">
                      <span className="text-xs text-pink-400 font-bold">[Photo]</span>
                    </div>
                  </div>
                  <h3 className="text-xl font-bold text-center text-gray-900 mb-2 group-hover:text-pink-600 transition-colors">{person.name}</h3>
                  <p className="text-xs text-center text-gray-500 mb-4 h-8">{person.company}</p>
                  
                  <div className="text-center">
                    <span className="inline-flex items-center text-sm font-bold text-pink-500">
                      インタビューを読む <ChevronRight className="w-4 h-4 ml-1 group-hover:translate-x-1 transition-transform" />
                    </span>
                  </div>
                </div>
              ))}
            </div>
          </div>
        );

      case 'visions':
        return (
          <div className="animate-fadeIn">
            <h2 className="text-3xl font-bold mb-8 border-b-4 border-pink-500 pb-2 inline-block">2026年 新年の抱負</h2>
            <p className="text-gray-600 mb-8">第40期の2026年がスタート！京ろまんグループの個性豊かなTOP陣営に展望を伺いました！（Vol.31より）</p>
            
            <div className="space-y-6">
              {VISIONS_2026.map((vision, index) => (
                <div key={index} className="bg-white p-6 md:p-8 rounded-2xl shadow-sm border-l-8 border-pink-500">
                  <div className="flex flex-col md:flex-row md:items-center justify-between mb-4 border-b border-pink-50 pb-4">
                    <div>
                      <p className="text-sm font-bold text-pink-500">{vision.role}</p>
                      <h3 className="text-2xl font-black text-gray-900">{vision.name}</h3>
                    </div>
                    <div className="hidden md:block w-16 h-16 bg-pink-50 rounded-full flex items-center justify-center border-2 border-white shadow-sm">
                       <span className="text-xs text-pink-300">[顔写真]</span>
                    </div>
                  </div>
                  
                  <div className="space-y-4">
                    <div>
                      <h4 className="text-sm font-bold bg-pink-50 text-pink-800 inline-block px-3 py-1 rounded-md mb-2">実現したい野望</h4>
                      <p className="text-gray-800 font-medium text-lg leading-relaxed">{vision.vision}</p>
                    </div>
                    <div>
                      <h4 className="text-sm font-bold bg-orange-50 text-orange-800 inline-block px-3 py-1 rounded-md mb-2">今年「初挑戦」してみたいこと</h4>
                      <p className="text-gray-600">{vision.challenge}</p>
                    </div>
                  </div>
                </div>
              ))}
            </div>
          </div>
        );

      case 'words':
        return (
          <div className="animate-fadeIn">
            <h2 className="text-3xl font-bold mb-8 border-b-4 border-pink-500 pb-2 inline-block">郡会長の言魂 アーカイブ</h2>
            <div className="grid grid-cols-2 md:grid-cols-4 gap-4">
              {WORDS.map((word, i) => (
                <div key={i} className="aspect-square bg-white rounded-2xl border border-pink-100 flex flex-col items-center justify-center p-4 hover:shadow-md hover:border-pink-300 transition-all cursor-pointer group">
                  <Quote className="text-pink-200 w-8 h-8 mb-2 group-hover:text-pink-400 transition-colors" />
                  <span className="font-bold text-gray-800 text-center mb-2">{word.month}</span>
                  {word.text ? (
                    <p className="text-xs text-pink-600 font-bold text-center line-clamp-3 px-2">「{word.text}」</p>
                  ) : (
                    <span className="text-xs text-gray-400 mt-2">[書道画像]</span>
                  )}
                </div>
              ))}
            </div>
          </div>
        );

      default:
        return null;
    }
  };

  return (
    <div className="min-h-screen bg-[#FFFDFD] text-gray-900 font-sans flex flex-col md:flex-row">
      
      {/* Mobile Header */}
      <div className="md:hidden bg-gradient-to-r from-pink-500 to-orange-400 text-white p-4 flex items-center justify-between sticky top-0 z-50 shadow-md">
        <h1 className="font-black text-xl tracking-widest flex items-center gap-2">
          <Heart className="w-5 h-5 fill-white" /> ネクストステージ
        </h1>
        <button onClick={() => setIsMobileMenuOpen(!isMobileMenuOpen)}>
          {isMobileMenuOpen ? <X /> : <Menu />}
        </button>
      </div>

      {/* Sidebar */}
      <aside className={`
        fixed md:sticky top-0 left-0 z-40 h-screen w-64 bg-white border-r border-pink-100 shadow-sm flex flex-col transition-transform duration-300 ease-in-out
        ${isMobileMenuOpen ? 'translate-x-0' : '-translate-x-full md:translate-x-0'}
      `}>
        <div className="p-6 hidden md:block border-b border-pink-50">
          <h2 className="text-xs font-bold text-pink-400 mb-1 tracking-widest flex items-center gap-1">
            <Heart className="w-3 h-3 fill-pink-400" /> 京ろまんグループ社内報
          </h2>
          <h1 className="text-2xl font-black tracking-widest text-gray-900">ネクスト<br/>ステージ</h1>
        </div>
        
        <nav className="flex-1 p-4 overflow-y-auto space-y-1">
          {navItems.map(item => (
            <button
              key={item.id}
              onClick={() => handleNavClick(item.id)}
              className={`
                w-full flex items-center gap-3 px-4 py-3 rounded-xl text-left transition-all font-medium
                ${activeTab === item.id 
                  ? 'bg-pink-50 text-pink-600 shadow-sm border-r-4 border-pink-500' 
                  : 'text-gray-600 hover:bg-pink-50/50 hover:text-pink-500'}
              `}
            >
              {item.icon}
              {item.label}
            </button>
          ))}
        </nav>

        <div className="p-4 border-t border-pink-50 text-xs text-gray-400 text-center bg-gray-50/50">
          © 夢・感動！委員会<br/>Kyo-Roman Group
        </div>
      </aside>

      {/* Overlay for mobile */}
      {isMobileMenuOpen && (
        <div 
          className="fixed inset-0 bg-black bg-opacity-40 z-30 md:hidden backdrop-blur-sm"
          onClick={() => setIsMobileMenuOpen(false)}
        />
      )}

      {/* Main Content */}
      <main className="flex-1 p-6 md:p-10 lg:p-12 overflow-x-hidden">
        {renderContent()}
      </main>

    </div>
  );
};

export default App;
