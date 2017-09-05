<template>
    <ul class="row grid cs-style-2">
      <li class="col-md-2 post" v-for="item in imginfos">
        <figure>
          <img :src="item.url">
          <figcaption>
            <h3>{{item.info.title}}</h3>
            <span>{{item.info.detail}}</span>
          </figcaption>
        </figure>
      </li>
    </ul>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App',
      imginfos: []
    }
  },
  created: function () {
    this.imginfos = [
      {
        url: 'static/images/uploads/1.jpg',
        info: {
          title: 'Music',
          detail: 'Jacob Cummings'
        }
      },
      {
        url: 'static/images/uploads/2.jpg',
        info: {
          title: 'Music',
          detail: 'Jacob Cummings'
        }
      },
      {
        url: 'static/images/uploads/3.jpg',
        info: {
          title: 'Music',
          detail: 'Jacob Cummings'
        }
      },
      {
        url: 'static/images/uploads/4.jpg',
        info: {
          title: 'Music',
          detail: 'Jacob Cummings'
        }
      },
      {
        url: 'static/images/uploads/5.jpg',
        info: {
          title: 'Music',
          detail: 'Jacob Cummings'
        }
      },
      {
        url: 'static/images/uploads/6.jpg',
        info: {
          title: 'Music',
          detail: 'Jacob Cummings'
        }
      },
      {
        url: 'static/images/uploads/7.jpg',
        info: {
          title: 'Music',
          detail: 'Jacob Cummings'
        }
      },
      {
        url: 'static/images/uploads/8.jpg',
        info: {
          title: 'Music',
          detail: 'Jacob Cummings'
        }
      },
      {
        url: 'static/images/uploads/9.jpg',
        info: {
          title: 'Music',
          detail: 'Jacob Cummings'
        }
      },
      {
        url: 'static/images/uploads/10.jpg',
        info: {
          title: 'Music',
          detail: 'Jacob Cummings'
        }
      },
      {
        url: 'static/images/uploads/11.jpg',
        info: {
          title: 'Music',
          detail: 'Jacob Cummings'
        }
      },
      {
        url: 'static/images/uploads/12.jpg',
        info: {
          title: 'Music',
          detail: 'Jacob Cummings'
        }
      },
      {
        url: 'static/images/uploads/13.jpg',
        info: {
          title: 'Music',
          detail: 'Jacob Cummings'
        }
      },
      {
        url: 'static/images/uploads/14.jpg',
        info: {
          title: 'Music',
          detail: 'Jacob Cummings'
        }
      },
      {
        url: 'static/images/uploads/15.jpg',
        info: {
          title: 'Music',
          detail: 'Jacob Cummings'
        }
      }
    ]
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
