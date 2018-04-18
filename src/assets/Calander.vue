<template>
  <div>
    <div class="container text-center">
    <h2 class="t-center">Sunridge Calendar of Events</h2>
    <img src="../assets/photos/vines2.png" width="600" alt="">
  </div>
   <div id="app">
    <vue-event-calendar
      :events="Events"
      @day-changed="handleDayChanged"
      @month-changed="handleMonthChanged"
    ></vue-event-calendar>
   </div>
  </div>
</template>

<script>
  let today = new Date()
  export default {
    name: 'app',
    data () {
      return {
        /*to add event follow the following*
        the format is going to be day-month-year.
        to get a month add it to today.getmonth() + 1 equals to feburary
        or today.getMonth() + 3 equals to april.
        to get the day have it follow by getMonth with /
        the full format is
        `${today.getFullYear()}/{today.getMonth() + 1}/01`
         the year(current year) month(ex. Feb)       date
          the format will look like: 01/02/2018.
          title: '' Add the title of the event
          desc: '' adds the description
         */
        Events: [
          {
            date: '07/05/2018',
                  //Day/Month/year
            title: '7 May - 6:30',
            desc: 'South Ogden Elementary Annual HOA Meeting'
          },
//          {
//            date: `${today.getFullYear()}/${today.getMonth()}/05`,
//            title: 'Title-1  day/month/year'
//          },
       ]
      }
    },
    methods: {
      handleDayChanged (data) {
        console.log('date-changed', data)
      },
      handleMonthChanged (data) {
        console.log('month-changed', data)
      }
    }
  }
</script>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    color: #2c3e50;
    margin-top: 30px;
    padding-top: 20px;
  }
  h1, h2, h3 {
    font-weight: normal;
    margin: 0;
    padding: 0;
  }

</style>
