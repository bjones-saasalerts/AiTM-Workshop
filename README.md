# AiTM-KConnect2025
Pre-reqs and reference material for Kaseya Connect Global 2025 AiTM Workshop


<style>
    /* Hosting Plans Section */
    .hosting-plans {
        display: flex;
        flex-wrap: nowrap;
        gap: 20px;
        justify-content: center;
        margin: 40px auto;
        max-width: 100%;
        overflow-x: auto;
        padding: 20px;
        box-sizing: border-box;
    }

    /* Individual Plan Cards */
    .plan-card {
        background: linear-gradient(145deg, #1a1a40, #2a2a70);
        border: 1px solid #3b3b9b;
        border-radius: 12px;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        padding: 20px;
        text-align: center;
        color: #e4e4ff;
        flex: 0 0 calc(20% - 20px);
        max-width: calc(20% - 20px);
        transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    /* Highlight Most Popular Card */
    .plan-card.most-popular {
        border: 2px solid #ffcc00;
        box-shadow: 0 8px 16px rgba(255, 204, 0, 0.5);
        position: relative;
    }

    .plan-card.most-popular::before {
        content: "MOST POPULAR";
        position: absolute;
        top: -12px;
        left: 50%;
        transform: translateX(-50%);
        background: #ffcc00;
        color: #000;
        padding: 5px 12px;
        font-size: 0.8rem;
        font-weight: bold;
        border-radius: 5px;
        z-index: 10;
        box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
    }

    .plan-card h3 {
        font-size: 1.4rem;
        margin-top: 20px;
        margin-bottom: 10px;
        color: #c8c8ff;
    }

    /* Pricing */
    .plan-card .price {
        font-size: 2rem;
        font-weight: bold;
        color: #ffcc00;
        margin: 15px 0;
    }

    /* Subtext */
    .plan-card .deploy {
        font-size: 0.9rem;
        color: #aaa;
        margin-bottom: 20px;
    }

    /* Features List */
    .plan-card ul {
        list-style-type: none;
        padding: 0;
        margin: 20px 0;
    }

    .plan-card ul li {
        margin-bottom: 10px;
        color: #d1d1ff;
        font-size: 0.95rem;
    }

    /* Button */
    .plan-card .btn {
        background: #5a5ad4;
        color: #fff;
        border: none;
        border-radius: 6px;
        padding: 10px 20px;
        cursor: pointer;
        font-size: 1rem;
        transition: background 0.3s ease, transform 0.3s ease;
        text-decoration: none;
        display: inline-block;
    }

    .plan-card .btn:hover {
        background: #4a4aa8;
        transform: translateY(-2px);
    }

    .gh-article-page-content {
        max-width: 1200px;
        margin: 0 auto;
        padding: 20px;
        width: 100%;
        box-sizing: border-box;
    }
</style>

<div class="hosting-plans">
    <div class="plan-card">
        <h3>1 GB</h3>
        <p class="price">$11.29/year</p>
        <p class="deploy">Deploy In: Multiple Datacenter Locations</p>
        <ul>
            <li>1 vCPU Core</li>
            <li>24 GB Pure SSD Storage</li>
            <li>1 GB RAM</li>
            <li>2000 GB Monthly Transfer</li>
            <li>1 Gbps Network Port</li>
            <li>Full Root Admin Access</li>
            <li>1 Dedicated IPv4 Address</li>
            <li>KVM / SolusVM Control Panel</li>
            <li>FREE Clientexec License</li>
        </ul>
        <a href="https://my.racknerd.com/aff.php?aff=10858&pid=903" class="btn" target="_blank">Order Now</a>
    </div>

    <div class="plan-card">
        <h3>2 GB</h3>
        <p class="price">$18.29/year</p>
        <p class="deploy">Deploy In: Multiple Datacenter Locations</p>
        <ul>
            <li>1 vCPU Core</li>
            <li>40 GB Pure SSD Storage</li>
            <li>2 GB RAM</li>
            <li>3500 GB Monthly Transfer</li>
            <li>1 Gbps Network Port</li>
            <li>Full Root Admin Access</li>
            <li>1 Dedicated IPv4 Address</li>
            <li>KVM / SolusVM Control Panel</li>
            <li>FREE Clientexec License</li>
        </ul>
        <a href="https://my.racknerd.com/aff.php?aff=10858&pid=904" class="btn" target="_blank">Order Now</a>
    </div>

    <div class="plan-card most-popular">
        <h3>3.5 GB</h3>
        <p class="price">$32.49/year</p>
        <p class="deploy">Deploy In: Multiple Datacenter Locations</p>
        <ul>
            <li>2 vCPU Cores</li>
            <li>65 GB Pure SSD Storage</li>
            <li>3.5 GB RAM</li>
            <li>7000 GB Monthly Transfer</li>
            <li>1 Gbps Network Port</li>
            <li>Full Root Admin Access</li>
            <li>1 Dedicated IPv4 Address</li>
            <li>KVM / SolusVM Control Panel</li>
            <li>FREE Clientexec License</li>
        </ul>
        <a href="https://my.racknerd.com/aff.php?aff=10858&pid=905" class="btn" target="_blank">Order Now</a>
    </div>

    <div class="plan-card">
        <h3>4 GB</h3>
        <p class="price">$43.88/year</p>
        <p class="deploy">Deploy In: Multiple Datacenter Locations</p>
        <ul>
            <li>3 vCPU Cores</li>
            <li>105 GB Pure SSD Storage</li>
            <li>4 GB RAM</li>
            <li>9000 GB Monthly Transfer</li>
            <li>1 Gbps Network Port</li>
            <li>Full Root Admin Access</li>
            <li>1 Dedicated IPv4 Address</li>
            <li>KVM / SolusVM Control Panel</li>
            <li>FREE Clientexec License</li>
        </ul>
        <a href="https://my.racknerd.com/aff.php?aff=10858&pid=906" class="btn" target="_blank">Order Now</a>
    </div>

    <div class="plan-card">
        <h3>6 GB</h3>
        <p class="price">$59.99/year</p>
        <p class="deploy">Deploy In: Multiple Datacenter Locations</p>
        <ul>
            <li>4 vCPU Cores</li>
            <li>140 GB Pure SSD Storage</li>
            <li>6 GB RAM</li>
            <li>12,000 GB Monthly Transfer</li>
            <li>1 Gbps Network Port</li>
            <li>Full Root Admin Access</li>
            <li>1 Dedicated IPv4 Address</li>
            <li>KVM / SolusVM Control Panel</li>
            <li>FREE Clientexec License</li>
        </ul>
        <a href="https://my.racknerd.com/aff.php?aff=10858&pid=907" class="btn" target="_blank">Order Now</a>
    </div>
</div>

