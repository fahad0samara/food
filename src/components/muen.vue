<template>
  <h1 class="text-6xl text-center font-mono py-20 text-pink-500 font-bold ml-5">
    Checkout <span class="text-black font-mono">our</span> menu.
  </h1>
<div class=" md:grid md:grid-cols-3  md:gap-7">
  <div class="" v-for="textod in textid" :key="textod.id">
    <div class=" -m-4   ">
      <div class="p-4  ">
        <div
          class=" shadow-red-600 shadow-xl border-t-2 border-red-600 border-2  border-opacity-60 rounded-lg overflow-hidden" 
        >
          <img
            class="  w-full  h-52 object-cover object-center"
            :src="textod.href"
            alt="blog"
          />
          <div class="p-6">
            <h2 class="tracking-widest text-xs title-font font-medium text-gray-400 mb-1">
              CATEGORY
            </h2>
            <h1 class="title-font text-2xl text-pink-500 font-bold mb-3">
           {{textod.name}}
            </h1>
            <p class="leading-relaxed mb-3">
            {{textod.text}}
            </p>
<h1 class="text-4xl text-red-600">{{textod.number}}{{textod.id}}</h1>
            <div class="flex items-center flex-wrap">
              <a class="text-indigo-500 inline-flex items-center md:mb-2 lg:mb-0 my-3"
                >Learn More
                <svg
                  class="w-4 h-4 ml-2"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  stroke-width="2"
                  fill="none"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                >
                  <path d="M5 12h14"></path>
                  <path d="M12 5l7 7-7 7"></path>
                </svg>
              </a>
              <span
                class="text-gray-400 mr-3 inline-flex items-center lg:ml-auto md:ml-0 ml-auto leading-none text-sm pr-3 py-1 border-r-2 border-gray-200"
              >
                <svg
                  class="w-4 h-4 mr-1"
                  stroke="currentColor"
                  stroke-width="2"
                  fill="none"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  viewBox="0 0 24 24"
                >
                  <path d="M1 12s4-8 11-8 11 8 11 8-4 8-11 8-11-8-11-8z"></path>
                  <circle cx="12" cy="12" r="3"></circle></svg
                >1.2K
              </span>
              <span class="text-gray-400 inline-flex items-center leading-none text-sm">
                <svg
                  class="w-4 h-4 mr-1"
                  stroke="currentColor"
                  stroke-width="2"
                  fill="none"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  viewBox="0 0 24 24"
                >
                  <path
                    d="M21 11.5a8.38 8.38 0 01-.9 3.8 8.5 8.5 0 01-7.6 4.7 8.38 8.38 0 01-3.8-.9L3 21l1.9-5.7a8.38 8.38 0 01-.9-3.8 8.5 8.5 0 014.7-7.6 8.38 8.38 0 013.8-.9h.5a8.48 8.48 0 018 8v.5z"
                  ></path></svg
                >6
              </span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  </div>
</template>

<script>
const textid = [
  {
    id: '$',
    number:3,
    name: "Catherine",
    text:
      "pupil hello wonder jet identity secret finest brass produce ought surrounded force ready well nearly dinner vessels bear facing body friend observe exact teach",
      href:'https://images-prod.healthline.com/hlcmsresource/images/AN_images/healthy-eating-ingredients-1296x728-header.jpg'
  },
  {
  id: '$',
    number:40,
    name: " pizza",
    text:
      "pupil hello wonder jet identity secret finest brass produce ought surrounded force ready well nearly dinner vessels bear facing body friend observe exact teach",
      href:'https://www.slowfoodonthego.com/wp-content/uploads/2021/07/s2.jpg'
  },
  {
    id: '$',
    number:50,
    name: "rice",
    text:
      "pupil hello wonder jet identity secret finest brass produce ought surrounded force ready well nearly dinner vessels bear facing body friend observe exact teach",
      href:'https://media.istockphoto.com/photos/cooked-rice-picture-id491090528?k=20&m=491090528&s=612x612&w=0&h=oKwbkVWhU_17ZBhB4v3SKOTGT85nmi2YS7KbPPa-x8o='
  },
  {id: '$',
    number:20,
    
    name: "pasta",
    text:
      "pupil hello wonder jet identity secret finest brass produce ought surrounded force ready well nearly dinner vessels bear facing body friend observe exact teach",
      href:'https://www.budgetbytes.com/wp-content/uploads/2013/07/Creamy-Spinach-Tomato-Pasta-bowl.jpg'
  },
  {
   id: '$',
    number:10,
    name: "",
    text:
      "pupil hello wonder jet identity secret finest brass produce ought surrounded force ready well nearly dinner vessels bear facing body friend observe exact teach",
      href:'https://wikiimg.tojsiabtv.com/wikipedia/commons/thumb/0/0b/RedDot_Burger.jpg/1280px-RedDot_Burger.jpg'
  },
  {
  id: '$',
    number:30,
    name: "pasta",
    text:
      "pupil hello wonder jet identity secret finest brass produce ought surrounded force ready well nearly dinner vessels bear facing body friend observe exact teach",
      href:'https://www.budgetbytes.com/wp-content/uploads/2013/07/Creamy-Spinach-Tomato-Pasta-bowl.jpg'
  },
  {
   id: '$',
    number:14,
    name: "pasta",
    text:
      "pupil hello wonder jet identity secret finest brass produce ought surrounded force ready well nearly dinner vessels bear facing body friend observe exact teach",
      href:'https://www.budgetbytes.com/wp-content/uploads/2013/07/Creamy-Spinach-Tomato-Pasta-bowl.jpg'
  },
  {
    id: '$',
    number:34,
    name: "pizza",
    text:
      "weak vast hang count vegetable effort rhythm heart completely south again magnet suit outer brain chamber hospital creature tiny finger thick glad stove tongue",
      href:'https://kupinica.com/wp-content/uploads/2014/03/pizza_fresca.jpg'
  },
  {
id: '$',
    number:17,
    name: "burger",
    text:
      "word television tent horse alike frozen increase evidence roof hay molecular dry least nervous silver contrast bend angry are belong promised split aid face",
      href:'https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQhDQSG5GB9tg5ZGHOqFzCaYRqk6MYWmkaQfCZqXSvAAh8MFxAYB0hGeHZAfZTCTHunzdE&usqp=CAU'
  },
  {
 id: '$',
    number:50,
    name: "pasta",
    text:
      "pupil hello wonder jet identity secret finest brass produce ought surrounded force ready well nearly dinner vessels bear facing body friend observe exact teach",
      href:'https://www.budgetbytes.com/wp-content/uploads/2013/07/Creamy-Spinach-Tomato-Pasta-bowl.jpg'
  },
  {
  id: '$',
    number:74,
    name: "burger",
    text:
      "flat play bright hung blood labor entire everywhere town short garage sun salmon every hat loud sunlight difference birthday upper cost oil farther sum",
      href:'https://www.emaratalyoum.com/polopoly_fs/1.1554652.1635401376!/image/image.jpg'
  },
  {
  id: '$',
    number:9,
    name: "donut",
    text:
      "conversation smooth city drop flat bridge receive tell accurate do ancient climate court tropical breakfast man type gasoline fifth equipment loss smallest please rear",
      href:'https://img.taste.com.au/f0YNQK61/taste/2016/11/donut-cake-70028-1.jpeg'
  },
  {
id: '$',
    number:41,
    name: "pasta",
    text:
      "pupil hello wonder jet identity secret finest brass produce ought surrounded force ready well nearly dinner vessels bear facing body friend observe exact teach",
      href:'https://www.budgetbytes.com/wp-content/uploads/2013/07/Creamy-Spinach-Tomato-Pasta-bowl.jpg'
  },
  {
  id: '$',
    number:32,
    name: "pizza",
    text:
      "hello wonder jet identity secret finest brass produce ought surrounded force ready well nearly dinner vessels bear facing body friend observe exact teach",
      href:'https://kupinica.com/wp-content/uploads/2014/03/pizza_fresca.jpg'
  },
  {
   id: '$',
    number:30,
    name: "rice",
    text:
      "exercise pitch took mostly kitchen guard author left became sound red listen birth largest sold dish gold pink drive ice apart along hung member",
      href:'https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQFK3FoXvlewonbPQrZWlvjNEIdhBn3VqbshX2zut9Tiu0__NnKrvPSGaqyMAg6p-Rapz8&usqp=CAU'
  },
  {
   id: '$',
    number:1,
    name: "dount markat",
    text:
      "desk society indicate led pale step so noise blew method involved skin flew directly highway lake top red drop private age mysterious film probably",
      href:'https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQCgGZ6-BsbZDrAMBox9xlVoIE-YrfbnTbfHA&usqp=CAU'
  },
  {
  id: '$',
    number:92,
    name: "pasta",
    text:
      "pupil hello wonder jet identity secret finest brass produce ought surrounded force ready well nearly dinner vessels bear facing body friend observe exact teach",
      href:'https://www.budgetbytes.com/wp-content/uploads/2013/07/Creamy-Spinach-Tomato-Pasta-bowl.jpg'
  },
  {
id: '$',
    number:20,
    name: "riec",
    text:
      "back differ frequently roof cage alike likely monkey tropical game declared silly direction bag daughter next hunter four equipment driven volume man master flew",
      href:'https://theonlyweighout.co.uk/wp-content/uploads/2020/03/basmati-300x300.png'
  },
  {id: '$',
    number:30,
    name: "pizza",
    text:
      "upon industrial may simplest fat determine such person structure horn free lose history slow pale seems nobody massage correctly felt shoot crack social tobacco",
      href:'https://i.ytimg.com/vi/8Q_9h6VKm9c/maxresdefault.jpg'
  },
  {id: '$',
    number:41,
    name: "pasta alla",
    text:
      "pupil hello wonder jet identity secret finest brass produce ought surrounded force ready well nearly dinner vessels bear facing body friend observe exact teach",
      href:'https://www.acozykitchen.com/wp-content/uploads/2018/12/PastaAllaVodka-7-scaled.jpg'
  },
  {
  id: '$',
    number:12,
    name: "dount",
    text:
      "pupil hello wonder jet identity secret finest brass produce ought surrounded force ready well nearly dinner vessels bear facing body friend observe exact teach",
      href:'https://media.istockphoto.com/vectors/donut-isolated-on-a-white-background-cute-colorful-and-glossy-donuts-vector-id1138438220?k=20&m=1138438220&s=612x612&w=0&h=b56x3agLh7L_mwwWQkoqCOf-zTybcP2S9PFTp75e4mg='
  },
  {id: '$',
    number:40,
    name: "pasta",
    text:
      "pupil hello wonder jet identity secret finest brass produce ought surrounded force ready well nearly dinner vessels bear facing body friend observe exact teach",
      href:'https://www.budgetbytes.com/wp-content/uploads/2013/07/Creamy-Spinach-Tomato-Pasta-bowl.jpg'
  },
  {
    id: '$',
    number:31,
    name: "burger",
    text:
      "jar tiny is back charge driver support related while political statement air giant elephant improve disease calm scientist round phrase birth spent tears magic",
      href:'https://www.emaratalyoum.com/polopoly_fs/1.1554652.1635401376!/image/image.jpg'
  },
  {
id: '$',
    number:20,
    name: "Zucchini Pasta",
    text:
      "With the help of the large holes on a box grater, zucchini transforms into a pile of soft shreds. Cook it down with olive oil, onion, and garlic and it becomes a creamy, caramelized mush ",
      href:'https://assets.bonappetit.com/photos/5f48ef0f683772f4cb97e816/6:9/w_1312,h_1968,c_limit/Basically-ZucchiniPasta05.jpg'
  },
  
  
  ];
export default {
  setup() {
    return {
      textid,
    };
  },
};
</script>
