# AngularPrac


**We will be creating Product List Management Application**

    ng new ProjName
    ng serve --open

Remove unnecessary htmls from App Component and add following html.

    <app-navbarcomponent></app-navbarcomponent>
    <div class="container">  
      <div class="row">
        <div class="col-12">
          <h1>{{ title }}</h1>
          <hr/>
        </div>
      </div>
      <div class="row">
        <div class="col-12">
          <p>
            <b>A product list is a document or database cataloguing a company's entire portfolio of goods or services.</b>        
          </p>      
        </div>    
      </div>
      <div class="row">
        <div class="col-12">
          <p>
            In marketing, a product is an object, or system, or service made available for consumer use as of the consumer demand; it is anything that can be offered to a market to satisfy the desire or need of a customer.[1] In retailing, products are often referred to as merchandise, and in manufacturing, products are bought as raw materials and then sold as finished goods. A service is also regarded as a type of product.
          </p>      
        </div>
      </div>
      <div class="row">
        <div class="col-12">
          <p>
            A product list includes details about a company's entire portfolio of products. A product list is intended to organize all of a business's goods, stock, price, sales history, etc. Often, it is necessary to make a product list before you can prepare invoices.
          </p>      
        </div>
      </div>
    </div>


**Add Bootstrap references in Index.html**
https://getbootstrap.com/docs/5.1/getting-started/introduction/


**Add Navbar component**

    ng g c navbarcomponent


