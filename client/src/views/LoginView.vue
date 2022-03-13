<script setup>
  
</script>

<template>
  <div class="login-page">
    <div class="loader">
      <div class="spinner-grow text-primary" role="status">
        <span class="sr-only">Loading...</span>
      </div>
    </div>
    <div class="container">
      <div class="row justify-content-md-center">
        <div class="col-md-12 col-lg-4">
          <div class="card login-box-container">
            <div class="card-body">
              <div class="authent-logo">
                <img src="@/assets/images/logo@2x.png" alt="" />
              </div>
              <div class="authent-text">
                <p>Welcome to UPT Server</p>
                <p>Please Sign-in to your account.</p>
              </div>

              <form>
                <div class="mb-3">
                  <div class="form-floating">
                    <input
                      type="text"
                      class="form-control"
                      id="floatingInput"
                      placeholder="NIM"
                      pattern="[0-9]{2}.?[0-9]{3}.?[0-9]{4}"
                      title="NIM Format: xx.xxx.xxxx"
                      required
                    />
                    <label for="floatingInput">NIM</label>
                  </div>
                </div>
                <div class="mb-3">
                  <div class="form-floating">
                    <input
                      type="password"
                      class="form-control"
                      id="floatingPassword"
                      placeholder="Password"
                      required
                    />
                    <label for="floatingPassword">Password</label>
                  </div>
                </div>
                <div class="mb-3 form-check">
                  <input
                    type="checkbox"
                    class="form-check-input"
                    id="exampleCheck1"
                  />
                  <label class="form-check-label" for="exampleCheck1"
                    >Check me out</label
                  >
                </div>
                <div class="d-grid">
                  <button type="submit" class="btn btn-info m-b-xs">
                    Sign In
                  </button>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
