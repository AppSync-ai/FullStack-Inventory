<!-- load header.php -->
<?php
$data['opened'] = 'dashboard';
$data['active_nav'] = 'home';
$data['title'] = 'Rappid Technologies';
$this->load->view('header', $data);
?>

<link rel="stylesheet" href="https://code.ionicframework.com/ionicons/2.0.1/css/ionicons.min.css">
<!-- Content Wrapper. Contains page content -->
<div class="content-wrapper text-light" style="background-color: #272D42;">
  <!-- Content Header (Page header) -->
  <div class="content-header ">
    <div class="container-fluid text-center">
      <h1 class="m-3 text-bold text-warning"><?php echo $this->config->item('project_title'); ?></h1>
      <h5 class="mt-2">Effortlessly handle your business inventory with ease, ensuring smooth operations</h5>
    </div><!-- /.container-fluid -->

    <a class="shadow-lg d-none" onclick="refresh_page()">
      <button class="floating-action-button sticky">
        <i class="fas fa-refresh"></i>
      </button>
    </a>

  </div>
  <!-- /.content-header -->

  <!-- Main content -->
  <div class="content">

    <div class="container-fluid">
      <div class="row pb-3 text-center" style="justify-content: center;">

        <div class="text-light col-lg-12 text-center">
          <h2><strong class="text-warning">Unlimited Everything</strong></h2>
          <hr class="bg-gray">
          <h4>Mobile App</h4>
          <h3 class="text-bold">Simple & Easy Features</h3>
          <hr class="bg-gray">

          <h4 class="text-center">Introduction to FullStack Inventory</h4>
          <div class="row">
            <iframe class="col-lg-6" width="100%" height="315" src="https://www.youtube.com/embed/bVHhbKGeuFU" frameborder="0" allowfullscreen></iframe>
            <iframe class="col-lg-6" width="100%" height="315" src="https://www.youtube.com/embed/AUYeerDCWkw" frameborder="0" allowfullscreen></iframe>
          </div>
        </div>

        <hr class="bg-gray col-12">

        <div class="col-lg-3 text-center p-3">
          <img src="<?php echo base_url('assets/images/img_1.png'); ?>" alt="" width="100%">
          <h4 class="text-bold">Dashboard</h4>
          <hr class="bg-gray mx-2 my-2">
          <h6 class="text-normal">Easy & User friendly dashboard</h6>
        </div>



        <div class="col-lg-3 text-center p-3">
          <img src="<?php echo base_url('assets/images/img_2.png'); ?>" alt="" width="100%">
          <h4 class="text-bold">Categories</h4>
          <hr class="bg-gray mx-2 my-2">
          <h6 class="text-normal">Effortlessly organize your categories for seamless management</h6>
        </div>

        <div class="col-lg-3 text-center p-3">
          <img src="<?php echo base_url('assets/images/img_3.png'); ?>" alt="" width="100%">
          <h4 class="text-bold">Products</h4>
          <hr class="bg-gray mx-2 my-2">
          <h6 class="text-normal">Effortlessly manage an unlimited number of products with ease, no hassle involved</h6>
        </div>

        <div class="col-lg-3 text-center p-3">
          <img src="<?php echo base_url('assets/images/img_4.png'); ?>" alt="" width="100%">
          <h4 class="text-bold">Warehouses</h4>
          <hr class="bg-gray mx-2 my-2">
          <h6 class="text-normal">Effortlessly oversee the stock in multiple warehouses for efficient inventory control</h6>
        </div>

        <div class="col-lg-3 text-center p-3">
          <img src="<?php echo base_url('assets/images/img_5.png'); ?>" alt="" width="100%">
          <h4 class="text-bold">Units</h4>
          <hr class="bg-gray mx-2 my-2">
          <h6 class="text-normal">You can customize the unit management to suit your business needs</h6>
        </div>

        <div class="col-lg-3 text-center p-3">
          <img src="<?php echo base_url('assets/images/img_6.png'); ?>" alt="" width="100%">
          <h4 class="text-bold">Suppliers / Party</h4>
          <hr class="bg-gray mx-2 my-2">
          <h6 class="text-normal">Effortlessly handle all your suppliers and partners within the app</h6>
        </div>

        <div class="col-lg-3 text-center p-3">
          <img src="<?php echo base_url('assets/images/img_7.png'); ?>" alt="" width="100%">
          <h4 class="text-bold">Inward / Outward</h4>
          <hr class="bg-gray mx-2 my-2">
          <h6 class="text-normal">Record incoming and outgoing entries to keep track of your inventory</h6>
        </div>

        <div class="col-lg-3 text-center p-3">
          <img src="<?php echo base_url('assets/images/img_8.png'); ?>" alt="" width="100%">
          <h4 class="text-bold">Transactions</h4>
          <hr class="bg-gray mx-2 my-2">
          <h6 class="text-normal">Easily view transactions by date and enjoy real-time synchronization anytime</h6>
        </div>

        <div class="col-lg-3 text-center p-3">
          <img src="<?php echo base_url('assets/images/img_9.png'); ?>" alt="" width="100%">
          <h4 class="text-bold">Basic Receipt</h4>
          <hr class="bg-gray mx-2 my-2">
          <h6 class="text-normal">Create a simple receipt for sharing with others</h6>
        </div>

        <div class="col-lg-3 text-center p-3">
          <img src="<?php echo base_url('assets/images/img_10.png'); ?>" alt="" width="100%">
          <h4 class="text-bold">Reports</h4>
          <hr class="bg-gray mx-2 my-2">
          <h6 class="text-normal">Generate Excel reports anytime for a broader overview</h6>
        </div>

        <div class="col-lg-3 text-center p-3">
          <img src="<?php echo base_url('assets/images/img_11.png'); ?>" alt="" width="100%">
          <h4 class="text-bold">Stock Shifting</h4>
          <hr class="bg-gray mx-2 my-2">
          <h6 class="text-normal">Easily transfer stock between warehouses</h6>
        </div>

        <div class="col-lg-3 text-center p-3">
          <img src="<?php echo base_url('assets/images/img_12.png'); ?>" alt="" width="100%">
          <h4 class="text-bold">Staff Management</h4>
          <hr class="bg-gray mx-2 my-2">
          <h6 class="text-normal">No per-user charges, you can have unlimited staff and admin accounts</h6>
        </div>

        <hr class="bg-gray mx-2 my-2">

        <div class="col-lg-6 text-center p-3">
          <h5>Checkout More</h5>
          <div class="row mt-3">
            <a href="<?php echo base_url() . '/desktop' ?>" class="col mx-2 btn btn-success" style="border-radius: 50px;"><i class="fa fa-desktop nav-icon mr-2"></i> Desktop Panel</a>
            <a href="https://rappid.in/pricing/fullstackinventory" class="col mx-2 btn btn-warning" style="border-radius: 50px;"><i class="fa fa-money nav-icon mr-2"></i> Pricing</a>
          </div>
          <div>
            <a href="https://wa.me/917387191410" class="col mx-2 mt-3 btn btn-primary" style="border-radius: 50px;"><i class="fa fa-sms nav-icon mr-2"></i> Connect on Whatsapp</a>
          </div>
        </div>


      </div>

      <div class="text-center py-3">
        <hr class="bg-gray">
        <h5 class="text-bold">Power Up Simplicity!</h5>
      </div>
      <!-- /.row -->
    </div><!-- /.container-fluid -->
  </div>
  <!-- /.content -->
</div>
<!-- /.content-wrapper -->

<?php $this->load->view('footer'); ?>

<script src="https://cdnjs.cloudflare.com/ajax/libs/jqueryui/1.12.1/jquery-ui.min.js"></script>
<script src="https://www.youtube.com/iframe_api"></script>
<script>
  var players = []; // Array to store YouTube player instances

  // This function is called when the YouTube API is ready
  function onYouTubeIframeAPIReady() {
    players[0] = new YT.Player('player1', {
      videoId: 'bVHhbKGeuFU',
      events: {
        'onStateChange': onPlayerStateChange
      }
    });
    players[1] = new YT.Player('player2', {
      videoId: 'AUYeerDCWkw',
      events: {
        'onStateChange': onPlayerStateChange
      }
    });
  }

  // This function is called when the player state changes (e.g., play, pause)
  function onPlayerStateChange(event) {
    if (event.data == YT.PlayerState.PLAYING) {
      // If one video starts playing, pause the other
      for (var i = 0; i < players.length; i++) {
        if (players[i] !== event.target) {
          players[i].pauseVideo();
        }
      }
    }
  }
</script>

<script>
  function refresh_page() {
    window.location.reload();
  }
</script>
