<template>
  <section>
    <div class="container">
    <div class="form-lacak">

        <div class="row align-items-center">
          <div class="col">
            <h5>From <span>*</span></h5>
          <div class="input-group mb-3 input-group-sm">
           
              <input type="search" class="form-control hide-focus border-info border-2 border-end-0 p-2" placeholder="Kecamatan Asal" aria-label="Username" aria-describedby="basic-addon1">
             
          </div>
          </div>
          <div class="col">
           <h5>Destination <span>*</span></h5>
          <div class="input-group mb-3 input-group-sm">
            
              <input type="search" class="form-control hide-focus border-info border-2 border-end-0 p-2" placeholder="Kecamatan Tujuan" aria-label="Username" aria-describedby="basic-addon1">
             
          </div>
          </div>
          <div class="col">
           <h5>Berat (Gram) <span>*</span></h5>
          <div class="input-group mb-3 input-group-sm">
           
              <input type="search" class="form-control hide-focus border-info border-2 border-end-0 p-2" placeholder="1000" aria-label="Username" aria-describedby="basic-addon1">
             
          </div>
          </div>
          <div class="col-1">

            <button class="cek">Cek</button>
          </div>
        </div>
      </div>
        
    </div>
    </section>
</template>

<style lang="scss" scoped>

.form-lacak{

  padding: 40px 30px;
  border-radius: 20px;
  box-shadow: rgba(0, 0, 0, 0.1) 0px 4px 12px;
  h5{
    font-size: 16px;
    color: #333;
    span{
      color: red;
    }
  }
  .cek{
    padding: 8px 22px;
    color: #fff;
    background: #8C46CF;
    border-radius: 100px;
    border: none;
    cursor: pointer;
  }
}
.hide-reveal > input[type="password"]::-ms-reveal {
  display: none;
}

.hide-focus:focus {
  outline: none !important;
  box-shadow: none !important;
  border-color: #ced4da !important;
}

.show_hide_password input {
  /* to hide the left border corners of button */
  z-index: 10;
}

.show_hide_password button {
  border-color: #ced4da #ced4da #ced4da transparent !important;
}


.placeholder-italics:placeholder-shown {
   font-style: italic;
}

.rounded-pill-end {
  border-top-right-radius: 50rem !important;
  border-bottom-right-radius: 50rem !important;
}

.rounded-pill-start {
  border-top-left-radius: 50rem !important;
  border-bottom-left-radius: 50rem !important;
}

.mw-max-c {
  max-width: max-content;
}

.rounded-4 {
  border-radius: 0.5rem !important;
}
</style>