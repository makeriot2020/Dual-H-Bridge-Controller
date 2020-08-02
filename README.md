# Dual-H-Bridge-Controller
PCB Manufacturing files(Gerber) for my through-hole component Dual H-Bridge Motor Controller

This is the gerber files for this project in a downloadable zip file.
If you find this useful, please consider making a small donation of $2.00 It will be appreciated
<div id="paypal-button-container"></div>
<script src="https://www.paypal.com/sdk/js?client-id=Ae10SkfLMKtNTginl9CqkbbKdP7EDGftq8fd_4plR6ONMFCtUSobpSZXq1dsqNyH_cNSj4yxS21eWbGH&currency=USD" data-sdk-integration-source="button-factory"></script>
<script>
  paypal.Buttons({
      style: {
          shape: 'pill',
          color: 'gold',
          layout: 'vertical',
          label: 'paypal',
          
      },
      createOrder: function(data, actions) {
          return actions.order.create({
              purchase_units: [{
                  amount: {
                      value: '2'
                  }
              }]
          });
      },
      onApprove: function(data, actions) {
          return actions.order.capture().then(function(details) {
              alert('Transaction completed by ' + details.payer.name.given_name + '!');
          });
      }
  }).render('#paypal-button-container');
</script>
