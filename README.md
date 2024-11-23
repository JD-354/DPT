<html><head><base href="javascript:void(0)" />

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Colección Sportsshoes - ZapatoStyle</title>



<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">



<style>

:root {

--primary-color: #FF5722;

--secondary-color: #2196F3;

}



body {

background: linear-gradient(135deg, #f5f5f5 0%, #fff 100%); font-family: 'Futura', 'Helvetica', Arial, sans-serif;

}



.navbar {

background: linear-gradient(90deg, #1a237e, #0d47a1) !important;

}



.product-card {

transition: transform 0.3s, box-shadow 0.3s; background: white;

border-radius: 15px;

box-shadow: 0 4px 15px rgba(0,0,0,0.1); margin-bottom: 25px;

overflow: hidden;

}



.product-card:hover { transform: translateY(-8px);

box-shadow: 0 8px 25px rgba(206, 17, 65, 0.2);

}



.product-price {

color: var(--primary-color); font-size: 1.4rem;

font-weight: bold;

}



.shop-btn {

 

background-color: var(--primary-color); color: white;

border: none; border-radius: 25px;

padding: 10px 25px; transition: all 0.3s;

}



.shop-btn:hover {

background-color: #f4511e; color: white;

transform: scale(1.05);

}



#cart-counter { position: relative; top: -10px;

right: -5px;

background-color: var(--primary-color); color: white;

border-radius: 50%; padding: 2px 6px; font-size: 12px;

transition: transform 0.2s;

}



.footer {

background-color: var(--secondary-color); color: white;

padding: 40px 0; margin-top: 50px;

}



.cart-item {

background-color: #f8f9fa; border-radius: 5px;

}



.modal-content { border-radius: 15px;

}



.modal-header {

background-color: var(--secondary-color); color: white;

border-top-left-radius: 15px;

 

border-top-right-radius: 15px;

}



.modal-header .btn-close { filter: invert(1);

}

</style>

</head>

<body>



<nav class="navbar navbar-expand-lg navbar-dark">

<div class="container">

<a class="navbar-brand" href="https://zapatostyle.com">

<i class="fas fa-running me-2"></i> Colección Sportsshoes

</a>



<button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">

<span class="navbar-toggler-icon"></span>

</button>



<div class="collapse navbar-collapse" id="navbarNav">

<ul class="navbar-nav me-auto">

<li class="nav-item">

<a class="nav-link" href="https://zapatostyle.com/shoes"><i class="fas fa-home"></i> Inicio</a>

</li>

<li class="nav-item">

<a class="nav-link" href="https://zapatostyle.com/running"><i class="fas fa-running"></i> Correr</a>

</li>

<li class="nav-item">

<a class="nav-link" href="https://zapatostyle.com/basketball"><i class="fas fa-basketball-ball"></i> Básquetbol</a>

</li>

<li class="nav-item">

<a class="nav-link" href="https://zapatostyle.com/training"><i class="fas fa-dumbbell"></i> Entrenamiento</a>

</li>

<li class="nav-item">

<a class="nav-link" href="https://zapatostyle.com/crosstraining"><i class="fas fa-shoe-prints"></i> Cross Training</a>

</li>

</ul>



<div class="cart-container">

<button class="btn btn-outline-light" data-bs-toggle="modal" data-bs-target="#checkoutModal">

<i class="fas fa-shopping-cart"></i>

 

<span id="cart-counter">0</span>

</button>

</div>

</div>

</div>

</nav>



<div class="container mt-5">

<h1 class="text-center mb-5">Colección Deportiva Sportsshoes</h1>



<div class="row">

<!-- Sportsshoes Sprint -->

<div class="col-md-4">

<div class="product-card p-3">

<img src="https://images.unsplash.com/photo-1595341888016-a392ef81b7de" alt="Sportsshoes Sprint, lightweight running shoe in blue and white" class="img-fluid mb-3" width="100%" height="300">

<h5>Sportsshoes Sprint Elite</h5>

<p class="product-price">$89.99</p>

<div class="d-flex justify-content-between">

<select class="form-select w-50 me-2">

<option>Size 7</option>

<option>Size 8</option>

<option>Size 9</option>

<option>Size 10</option>

<option>Size 11</option>

<option>Size 12</option>

</select>

<button class="btn shop-btn flex-grow-1">Agregar al Carrito</button>

</div>

</div>

</div>



<!-- Sportsshoes Trail Runner -->

<div class="col-md-4">

<div class="product-card p-3">

<img src="https://images.unsplash.com/photo-1551107696-a4b0c5a0d9a2" alt="Sportsshoes Trail Runner, rugged outdoor shoe in green and black" class="img-fluid mb-3" width="100%" height="300">

<h5>Sportsshoes Trail Runner X2</h5>

<p class="product-price">$120.00</p>

<div class="d-flex justify-content-between">

<select class="form-select w-50 me-2">

<option>Size 7</option>

<option>Size 8</option>

<option>Size 9</option>

<option>Size 10</option>

<option>Size 11</option>

 

<option>Size 12</option>

</select>

<button class="btn shop-btn flex-grow-1">Agregar al Carrito</button>

</div>

</div>

</div>



<!-- Sportsshoes CrossFit -->

<div class="col-md-4">

<div class="product-card p-3">

<img src="https://images.unsplash.com/photo-1556906781-9a412961c28c" alt="Sportsshoes CrossFit, versatile training shoe in black and red" class="img-fluid mb-3" width="100%" height="300">

<h5>Sportsshoes CrossFit Pro</h5>

<p class="product-price">$135.00</p>

<div class="d-flex justify-content-between">

<select class="form-select w-50 me-2">

<option>Size 7</option>

<option>Size 8</option>

<option>Size 9</option>

<option>Size 10</option>

<option>Size 11</option>

<option>Size 12</option>

</select>

<button class="btn shop-btn flex-grow-1">Agregar al Carrito</button>

</div>

</div>

</div>



<!-- Sportsshoes Marathon -->

<div class="col-md-4">

<div class="product-card p-3">

<img src="https://images.unsplash.com/photo-1595950653106-6c9ebd614d3a" alt="Sportsshoes Marathon, professional running shoe in blue and orange" class="img-fluid mb-3" width="100%" height="300">

<h5>Sportsshoes Marathon Pro</h5>

<p class="product-price">$145.00</p>

<div class="d-flex justify-content-between">

<select class="form-select w-50 me-2">

<option>Size 7</option>

<option>Size 8</option>

<option>Size 9</option>

<option>Size 10</option>

<option>Size 11</option>

<option>Size 12</option>

</select>

<button class="btn shop-btn flex-grow-1">Agregar al Carrito</button>

</div>

 

</div>

</div>



<!-- Sportsshoes Trainer -->

<div class="col-md-4">

<div class="product-card p-3">

<img src="https://images.unsplash.com/photo-1539185441755-769473a23570" alt="Sportsshoes Trainer, versatile training shoe in black and white" class="img-fluid mb-3" width="100%" height="300">

<h5>Sportsshoes Trainer Elite</h5>

<p class="product-price">$95.00</p>

<div class="d-flex justify-content-between">

<select class="form-select w-50 me-2">

<option>Size 7</option>

<option>Size 8</option>

<option>Size 9</option>

<option>Size 10</option>

<option>Size 11</option>

<option>Size 12</option>

</select>

<button class="btn shop-btn flex-grow-1">Agregar al Carrito</button>

</div>

</div>

</div>



<!-- Sportsshoes Fitness -->

<div class="col-md-4">

<div class="product-card p-3">

<img src="https://images.unsplash.com/photo-1542291026-7eec264c27ff" alt="Sportsshoes Fitness, gym training shoe in grey and red" class="img-fluid mb-3" width="100%" height="300">

<h5>Sportsshoes Fitness Max</h5>

<p class="product-price">$105.00</p>

<div class="d-flex justify-content-between">

<select class="form-select w-50 me-2">

<option>Size 7</option>

<option>Size 8</option>

<option>Size 9</option>

<option>Size 10</option>

<option>Size 11</option>

<option>Size 12</option>

</select>

<button class="btn shop-btn flex-grow-1">Agregar al Carrito</button>

</div>

</div>

</div>

</div>

</div>

 

<div class="modal fade" id="checkoutModal" tabindex="-1">

<div class="modal-dialog modal-lg">

<div class="modal-content">

<div class="modal-header">

<h5 class="modal-title">Finalizar Compra</h5>

<button type="button" class="btn-close" data-bs-dismiss="modal"></button>

</div>

<div class="modal-body">

<div class="row">

<div class="col-md-6">

<h6>Artículos en el Carrito</h6>

<div id="cartItems" class="mb-3">

<!-- Cart items will be dynamically added here -->

</div>

</div>

<div class="col-md-6">

<h6>Información del Cliente</h6>

<form id="checkoutForm">

<div class="mb-3">

<label class="form-label">Nombre Completo</label>

<input type="text" name="fullName" class="form-control" required>

</div>

<div class="mb-3">

<label class="form-label">Correo Electrónico</label>

<input type="email" name="email" class="form-control" required>

</div>

<div class="mb-3">

<label class="form-label">Teléfono</label>

<input type="tel" name="phone" class="form-control" required>

</div>

<div class="mb-3">

<label class="form-label">Dirección</label>

<textarea name="address" class="form-control" rows="2" required></textarea>

</div>

<div class="mb-3">

<label class="form-label">País</label>

<select name="country" class="form-select" required>

<option value="">Seleccionar País</option>

<option value="USA">Estados Unidos</option>

<option value="MEX">México</option>

<option value="CAN">Canadá</option>

</select>

</div>

<button type="submit" class="btn shop-btn w-100">Completar Compra</button>

</form>

 

</div>

</div>

</div>

</div>

</div>

</div>



<footer class="footer">

<div class="container">

<div class="row">

<div class="col-md-4">

<h5>Contáctanos</h5>

<p><i class="fas fa-phone"></i> +1 234 567 890</p>

<p><i class="fas fa-envelope"></i> jordan@zapatostyle.com</p>

</div>

<div class="col-md-4">

<h5>Síguenos</h5>

<a href="https://facebook.com/airjordan" class="text-white me-3"><i class="fab fa-facebook"></i></a>

<a href="https://instagram.com/jumpman23" class="text-white me-3"><i class="fab fa- instagram"></i></a>

<a href="https://twitter.com/jumpman23" class="text-white"><i class="fab fa-twitter"></i></a>

</div>

<div class="col-md-4">

<h5>Boletín Informativo</h5>

<p>Mantente actualizado con los últimos lanzamientos</p>

<form class="d-flex">

<input type="email" class="form-control me-2" placeholder="Tu correo electrónico">

<button class="btn shop-btn">Suscribirse</button>

</form>

</div>

</div>

</div>

</footer>



<script>

let cartItems = []; let cartCount = 0;



document.querySelectorAll('.shop-btn').forEach(button => { if(button.textContent.includes('Agregar al Carrito')) {

button.addEventListener('click', () => {

const productCard = button.closest('.product-card');

const productName = productCard.querySelector('h5').textContent;

const productPrice = productCard.querySelector('.product-price').textContent; const productSize = productCard.querySelector('select').value;

 

cartItems.push({

name: productName,

price: parseFloat(productPrice.replace('$', '')), size: productSize

});



cartCount++;

document.getElementById('cart-counter').textContent = cartCount;



const counter = document.getElementById('cart-counter'); counter.style.transform = 'scale(1.5)';

setTimeout(() => { counter.style.transform = 'scale(1)';

}, 200);



updateCartDisplay();



 

















}

});

 

// Add success message

const toast = document.createElement('div');

toast.className = 'alert alert-success position-fixed bottom-0 end-0 m-3'; toast.innerHTML = `¡${productName} agregado al carrito!`; document.body.appendChild(toast);

setTimeout(() => toast.remove(), 2000);

});

 



function updateCartDisplay() {

const cartItemsDiv = document.getElementById('cartItems'); cartItemsDiv.innerHTML = '';

let subtotal = 0; cartItems.forEach((item, index) => {

subtotal += item.price;

const itemDiv = document.createElement('div'); itemDiv.className = 'cart-item mb-2 p-2 border-bottom'; itemDiv.innerHTML = `

<div class="d-flex justify-content-between">

<div>

<div>${item.name}</div>

<small class="text-muted">${item.size}</small>

</div>

<div class="d-flex align-items-center">

<div class="me-3">$${item.price.toFixed(2)}</div>

<button class="btn btn-sm btn-danger" onclick="removeItem(${index})">

 

<i class="fas fa-trash"></i>

</button>

</div>

</div>

`;

cartItemsDiv.appendChild(itemDiv);

});



const tax = subtotal * 0.16; // 16% tax const total = subtotal + tax;



// Add order summary

const summaryDiv = document.createElement('div'); summaryDiv.className = 'border-top pt-3 mt-3'; summaryDiv.innerHTML = `

<div class="d-flex justify-content-between mb-2">

<div>Subtotal:</div>

<div>$${subtotal.toFixed(2)}</div>

</div>

<div class="d-flex justify-content-between mb-2">

<div>Impuesto (16%):</div>

<div>$${tax.toFixed(2)}</div>

</div>

<div class="d-flex justify-content-between fw-bold">

<div>Total:</div>

<div>$${total.toFixed(2)}</div>

</div>

`; cartItemsDiv.appendChild(summaryDiv);

}



function removeItem(index) { cartItems.splice(index, 1); cartCount--;

document.getElementById('cart-counter').textContent = cartCount; updateCartDisplay();

}



document.getElementById('checkoutForm').addEventListener('submit', function(e) { e.preventDefault();



// Get form data

const formData = new FormData(e.target); const customerInfo = {

name: formData.get('fullName'), email: formData.get('email'),

 

phone: formData.get('phone'), address: formData.get('address'), country: formData.get('country')

};



// Create order summary const orderSummary = `

Resumen del Pedido:

==================

Información del Cliente:

Nombre: ${customerInfo.name} Correo: ${customerInfo.email} Teléfono: ${customerInfo.phone} Dirección: ${customerInfo.address} País: ${customerInfo.country}



Artículos Pedidos:

${cartItems.map(item => `- ${item.name} (${item.size}): $${item.price.toFixed(2)}`).join('\n')}



Monto Total: $${(cartItems.reduce((acc, item) => acc + item.price, 0) * 1.16).toFixed(2)}

`;



alert('¡Gracias por tu compra!\n\n' + orderSummary);



// Reset cart cartItems = []; cartCount = 0;

document.getElementById('cart-counter').textContent = '0'; updateCartDisplay();

document.querySelector('[data-bs-dismiss="modal"]').click(); e.target.reset();

});

</script>



</body>

</html>

