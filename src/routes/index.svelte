<script>
  import BoxInfo from '../components/infos_box.svelte';
</script>

<main>
    <header>
        <div class="flex font-medium px-8 justify-center pt-8 pb-4">
            <h3 class="pr-10 relative top-2 right-20 text-2xl font-black">Today</h3>
            <svg xmlns="http://www.w3.org/2000/svg" class="relative left-20 top-3" width="30.294" height="30.294" viewBox="0 0 30.294 30.294">
                <g id="Add_City_Button_Small" data-name="Add City Button Small" transform="translate(-20 -421)">
                  <g id="Ellipse_1" data-name="Ellipse 1" transform="translate(20 421)" fill="none" stroke="#0076ff" stroke-width="3">
                    <circle cx="15.147" cy="15.147" r="15.147" stroke="none"/>
                    <circle cx="15.147" cy="15.147" r="13.647" fill="none"/>
                  </g>
                  <g id="Groupe_1" data-name="Groupe 1" transform="translate(27.268 428.347)">
                    <path id="Tracé_1" data-name="Tracé 1" d="M228.976,442.163v15.746" transform="translate(-221.103 -442.163)" fill="none" stroke="#0076ff" stroke-width="3"/>
                    <path id="Tracé_2" data-name="Tracé 2" d="M0,0V15.746" transform="translate(15.746 7.873) rotate(90)" fill="none" stroke="#0076ff" stroke-width="3"/>
                  </g>
                </g>
              </svg>              
        </div>
    </header>
    
    <section class="pb-10">
      <BoxInfo></BoxInfo>
      <BoxInfo></BoxInfo>
      <BoxInfo></BoxInfo>
    </section>

    <section>
      <div class="flex pb-12 justify-center">
        <button style="background-color: #0076FF;" class="text-sm border rounded-xl text-white py-3 px-9 font-black">+ Add City</button>
      </div>

    </section>

</main>

<style>
    body{
      background-color: #FFFFFF;
    }
</style>