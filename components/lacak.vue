<template>
    <div>
      <div class="card">
       <div class="card-body">
          <h5>Form </h5>
          <div class="input-group mb-3 input-group-sm">
            <select class="form-select border-0 bg-warning text-white rounded-pill-start mw-max-c" id="inputGroupSelect01">
              <option selected>All</option>
              <option value="1">One</option>
              <option value="2">Two</option>
              <option value="3">Three</option>
            </select>
              <input type="search" class="form-control hide-focus border-warning border-2 border-end-0" placeholder="" aria-label="Username" aria-describedby="basic-addon1">
              <span class="input-group-text bg-white border-warning rounded-pill-end border-2 border-start-0 ps-1" id="basic-addon1"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="var(--bs-warning)" stroke="var(--bs-warning)" class="bi bi-search" viewBox="0 0 16 16">
                  <path d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z" />
                </svg></span>
          </div>
          <h5>Destination</h5>
          <div class="input-group mb-3 input-group-sm">
            <select class="form-select border-0 bg-warning text-white rounded-pill-start mw-max-c" id="inputGroupSelect01">
              <option selected>All</option>
              <option value="1">One</option>
              <option value="2">Two</option>
              <option value="3">Three</option>
            </select>
              <input type="search" class="form-control hide-focus border-warning border-2 border-end-0" placeholder="" aria-label="Username" aria-describedby="basic-addon1">
              <span class="input-group-text bg-white border-warning rounded-pill-end border-2 border-start-0 ps-1" id="basic-addon1"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="var(--bs-warning)" stroke="var(--bs-warning)" class="bi bi-search" viewBox="0 0 16 16">
                  <path d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z" />
                </svg></span>
          </div>
          <h5>Berat (Gram)</h5>
          <div class="input-group mb-3 input-group-sm">
            <select class="form-select border-0 bg-warning text-white rounded-pill-start mw-max-c" id="inputGroupSelect01">
              <option selected>All</option>
              <option value="1">One</option>
              <option value="2">Two</option>
              <option value="3">Three</option>
            </select>
              <input type="search" class="form-control hide-focus border-warning border-2 border-end-0" placeholder="" aria-label="Username" aria-describedby="basic-addon1">
              <span class="input-group-text bg-white border-warning rounded-pill-end border-2 border-start-0 ps-1" id="basic-addon1"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="var(--bs-warning)" stroke="var(--bs-warning)" class="bi bi-search" viewBox="0 0 16 16">
                  <path d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z" />
                </svg></span>
          </div>
        </div>
      </div>
    </div>
</template>

<style>
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