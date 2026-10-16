1. Portfolio project (script.js)

projects list me ek line jodo, aur image assets/portfolio/ folder me rakho.

js
{ title: "Sharma Coaching", type: "Website Development",
  description: "Course pages, fee details and an enquiry form.",
  image: "sharma-coaching.jpg", link: "https://example.com" },

Agar site live nahi hai to link: "" rakho. Agar image nahi hai to image: "" rakho.

2. Testimonial (testimonials.html)

<div class="portfolio-grid"> ke andar paste karo.

html
<figure class="card quote">
  <blockquote><p>Shivam ne meri website time par bana di aur ab roz enquiries aa rahi hain.</p></blockquote>
  <figcaption><strong>Rahul Sharma</strong><span>Coaching center owner, Lucknow</span></figcaption>
</figure>
3. Blog card (blog.html)

<div class="portfolio-grid"> ke andar paste karo.

html
<article class="card">
  <time class="post-date">20 Oct 2026</time>
  <h3>Your post title</h3>
  <p>Ek ya do line ka short summary.</p>
  <a class="project-link" href="post-my-new-post">Read more</a>
</article>
4. Naya blog post page

Kisi bhi post-*.html ki copy banao, jaise post-my-new-post.html. Phir ye 4 jagah badlo.

a) <title> aur description (head me):

html
<title>Your post title | Shivam Bharti</title>
<meta name="description" content="Short summary of the post.">

b) <main> ke andar ka poora hissa:

html
<section class="page-hero">
  <div class="container">
    <h1>Your post title</h1>
    <time class="post-date">20 Oct 2026</time>
  </div>
</section>

<section class="section">
  <div class="container">
    <article class="article">
      <p>Pehla paragraph.</p>
      <p>Doosra paragraph.</p>
      <p>Teesra paragraph.</p>
      <div class="btn-row">
        <a href="blog" class="btn btn-outline">All posts</a>
        <a class="btn btn-wa" data-wa="Hi Shivam, I read your blog post and need help with my website." target="_blank" rel="noopener">Ask me on WhatsApp</a>
      </div>
    </article>
  </div>
</section>

Post me heading chahiye to <p> ke beech me <h2>Sub heading</h2> daal do.

5. Service card (services.html)

<div class="services-grid"> ke andar paste karo.

html
<article class="card">
  <h3>SEO Setup</h3>
  <p>Simple SEO so your business shows up when people search in Lucknow.</p>
  <a class="wa-link" data-wa="Hi Shivam, I need SEO for my website. Can you help me?" target="_blank" rel="noopener">Ask on WhatsApp</a>
</article>

Services ke 4 cards index.html ke services preview me bhi hain. Wahan same card bina wa-link ke daalo.

6. Process step (process.html)

<ol class="steps"> ke andar paste karo. Number apne aap lag jaata hai.

html
<li>
  <h3>Step title</h3>
  <p>Is step me kya hota hai, ek ya do line me.</p>
</li>
7. Naye page ko menu me jodna

Har HTML file ke <ul> menu me ye line jodo.

html
<li><a href="pricing">Pricing</a></li>
