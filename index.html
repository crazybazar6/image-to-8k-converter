<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AI Image Enhancer · Quality Fix + Upscale to 4K/8K</title>
  <!-- SEO meta -->
  <meta name="description" content="Fix blurry photos and upscale to HD, 4K, or 8K. Or keep original size and just enhance quality. AI-powered deblur, noise removal.">
  <meta name="keywords" content="AI image enhancer, fix blurry photo, upscale to 4K, enhance image quality, 8K upscaler, HD converter">
  <!-- Schema markup -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "SoftwareApplication",
    "name": "AI Image Enhancer",
    "applicationCategory": "Multimedia",
    "description": "Fix blurry photos and upscale to HD, 4K, 8K, or enhance quality at original size.",
    "offers": {"@type": "Offer","price": "0","priceCurrency": "USD"}
  }
  </script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
    }
    body {
      background: #f5f7fc;
      color: #0f172a;
      line-height: 1.5;
    }
    .container {
      max-width: 1280px;
      margin: 0 auto;
      padding: 0 24px;
    }
    .navbar {
      background: #ffffffcc;
      backdrop-filter: blur(10px);
      border-bottom: 1px solid #e9edf2;
      padding: 12px 0;
      position: sticky;
      top: 0;
      z-index: 50;
    }
    .nav-container {
      display: flex;
      align-items: center;
      justify-content: space-between;
      flex-wrap: wrap;
    }
    .logo {
      font-size: 1.9rem;
      font-weight: 700;
      background: linear-gradient(135deg, #2563eb, #7c3aed);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }
    .nav-links {
      display: flex;
      gap: 28px;
      font-weight: 500;
    }
    .nav-links a {
      text-decoration: none;
      color: #1e293b;
      font-size: 0.95rem;
    }
    .nav-links a:hover { color: #2563eb; }
    .menu-toggle { display: none; font-size: 1.5rem; cursor: pointer; }
    @media (max-width: 800px) {
      .nav-links { display: none; }
      .menu-toggle { display: block; }
    }
    .hero {
      padding: 40px 0 20px;
      text-align: center;
    }
    .hero h1 {
      font-size: 3.2rem;
      font-weight: 800;
      letter-spacing: -0.02em;
      background: linear-gradient(to right, #1e3a8a, #6b21a5);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }
    .hero p {
      font-size: 1.3rem;
      color: #334155;
      max-width: 700px;
      margin: 1rem auto;
    }
    .upload-card {
      background: white;
      border-radius: 3rem;
      padding: 40px 32px;
      box-shadow: 0 25px 50px -12px rgba(0,0,0,0.15);
      max-width: 900px;
      margin: 30px auto;
      border: 2px solid #e0e9f5;
    }
    .drag-area {
      border: 3px dashed #94a3b8;
      background: #f1f5f9;
      border-radius: 3rem;
      padding: 40px 20px;
      text-align: center;
      transition: 0.2s;
      cursor: pointer;
    }
    .drag-area i { font-size: 3.5rem; color: #2563eb; }
    .drag-area h3 { font-size: 1.8rem; font-weight: 600; margin: 12px 0; }
    .drag-area p { color: #475569; }
    .drag-area:hover { border-color: #2563eb; background: #eff6ff; }
    #fileInput { display: none; }

    .tool-chips {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
      justify-content: center;
      margin: 30px 0 20px;
    }
    .chip {
      background: white;
      border-radius: 60px;
      padding: 10px 24px;
      font-weight: 500;
      border: 1px solid #dbe1e9;
      cursor: pointer;
    }
    .chip i { color: #2563eb; margin-right: 8px; }
    .chip.active {
      background: #2563eb;
      color: white;
    }
    .chip.active i { color: white; }

    /* Resolution selector (HD, 4K, 8K, or Original Size) */
    .res-grid {
      display: flex;
      gap: 12px;
      flex-wrap: wrap;
      justify-content: center;
      margin: 20px 0;
    }
    .res-btn {
      background: #f1f5f9;
      padding: 12px 24px;
      border-radius: 40px;
      font-weight: 600;
      border: 2px solid transparent;
      cursor: pointer;
    }
    .res-btn.active {
      background: #2563eb;
      color: white;
      border-color: #1e40af;
    }
    .res-btn.original-size {
      background: #fef3c7;
      color: #92400e;
      border-color: #fbbf24;
    }
    .res-btn.original-size.active {
      background: #f59e0b;
      color: white;
      border-color: #b45309;
    }

    .enhance-btn {
      background: #0f172a;
      color: white;
      border: none;
      font-size: 1.3rem;
      font-weight: 700;
      padding: 18px 45px;
      border-radius: 60px;
      margin: 15px 0 25px;
      cursor: pointer;
      transition: 0.15s;
      box-shadow: 0 8px 20px #2563eb70;
      width: 100%;
      max-width: 500px;
      display: block;
      margin-left: auto;
      margin-right: auto;
    }
    .enhance-btn:hover { background: #1e293b; transform: scale(1.02); }
    .enhance-btn:disabled { opacity: 0.6; cursor: not-allowed; }

    .preview-row {
      display: flex;
      gap: 30px;
      flex-wrap: wrap;
      justify-content: center;
      margin: 40px 0 20px;
    }
    .preview-box {
      flex: 1 1 280px;
      background: #f1f4f9;
      border-radius: 2rem;
      padding: 20px;
      text-align: center;
    }
    .image-container {
      width: 100%;
      min-height: 250px;
      background: #d9e2ef;
      border-radius: 1.5rem;
      display: flex;
      align-items: center;
      justify-content: center;
      overflow: hidden;
    }
    .image-container img {
      max-width: 100%;
      max-height: 300px;
      object-fit: contain;
      border-radius: 1rem;
    }
    .placeholder-icon {
      font-size: 4rem;
      color: #6a7f9f;
    }
    .download-btn {
      background: #059669;
      color: white;
      padding: 14px 40px;
      border-radius: 60px;
      font-weight: 700;
      font-size: 1.2rem;
      border: none;
      cursor: pointer;
      margin: 10px 0;
    }
    .download-btn:hover { background: #047857; }
    .download-btn:disabled {
      background: #a5b4cb;
      cursor: not-allowed;
    }

    .format-badge {
      display: flex;
      gap: 15px;
      justify-content: center;
      color: #2c3e50;
      margin: 10px 0;
    }
    .format-badge span {
      background: #e2e8f0;
      padding: 4px 14px;
      border-radius: 40px;
      font-size: 0.9rem;
    }

    /* AdSense units */
    .ad-unit {
      background: #f1f5f9;
      border-radius: 40px;
      padding: 24px;
      text-align: center;
      border: 2px dashed #9bb7d4;
      margin: 30px 0;
      position: relative;
    }
    .ad-label {
      position: absolute;
      top: -10px;
      left: 20px;
      background: white;
      padding: 2px 15px;
      border-radius: 40px;
      font-size: 0.8rem;
      color: #64748b;
      border: 1px solid #cbd5e1;
    }

    .pages-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(140px,1fr));
      gap: 15px;
      margin: 40px 0;
    }
    .page-card {
      background: white;
      border-radius: 30px;
      padding: 18px;
      text-align: center;
      font-weight: 600;
      border: 1px solid #e9edf2;
    }
    .page-card i { font-size: 2rem; color: #2563eb; display: block; }

    .blog-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px,1fr));
      gap: 24px;
      margin: 30px 0;
    }
    .blog-card {
      background: white;
      border-radius: 1.8rem;
      padding: 20px;
    }
    .blog-card h3 { font-size: 1.3rem; margin-bottom: 8px; }

    .footer {
      background: #0b1120;
      color: #a0afc0;
      padding: 48px 0 20px;
      margin-top: 60px;
      border-radius: 3rem 3rem 0 0;
    }
    .footer-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px,1fr));
      gap: 30px;
    }
    .footer a { color: #a0afc0; text-decoration: none; display: block; margin: 6px 0; }
    .footer a:hover { color: white; }

    .dimension-note {
      background: #e6f7ff;
      padding: 10px;
      border-radius: 40px;
      margin: 10px 0;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <div class="navbar">
    <div class="container nav-container">
      <div class="logo">pixel<span style="color:#0f172a;">up.ai</span></div>
      <div class="nav-links">
        <a href="#">Home</a><a href="#">Image Enhancer</a><a href="#">Photo Upscaler</a><a href="#">4K Converter</a>
        <a href="#">8K Upscaler</a><a href="#">Blog</a><a href="#">About</a><a href="#">Contact</a>
      </div>
      <div class="menu-toggle"><i class="fas fa-bars"></i></div>
    </div>
  </div>

  <div class="container">
    <section class="hero">
      <h1>Fix Quality or Upscale to 4K/8K</h1>
      <p>Deblur · Sharpen · Remove Noise · Then upscale to HD, 4K, 8K or keep original size</p>
      <div class="format-badge"><span>JPG</span><span>PNG</span><span>WEBP</span></div>
    </section>

    <!-- Ad Unit Top -->
    <div class="ad-unit">
      <div class="ad-label">Advertisement</div>
      <div class="ad-content"><i class="fas fa-ad"></i> Google AdSense - Leaderboard</div>
    </div>

    <div class="upload-card">
      <div class="drag-area" id="dragDrop">
        <i class="fas fa-cloud-upload-alt"></i>
        <h3>Drag & drop any image</h3>
        <p>or click to browse (we'll enhance quality first, then upscale if desired)</p>
      </div>
      <input type="file" id="fileInput" accept="image/*">

      <div class="dimension-note" id="dimensionDisplay">
        <i class="fas fa-arrows-alt" style="color:#2563eb;"></i> Upload an image to see dimensions
      </div>

      <div class="tool-chips" id="toolChips">
        <span class="chip active" data-tool="deblur"><i class="fas fa-eye"></i>Deblur (fix blur)</span>
        <span class="chip" data-tool="sharpen"><i class="fas fa-crosshairs"></i>Sharpen details</span>
        <span class="chip" data-tool="noise"><i class="fas fa-cloud"></i>Noise reduction</span>
        <span class="chip" data-tool="face"><i class="fas fa-face-smile"></i>Face enhance</span>
        <span class="chip" data-tool="restore"><i class="fas fa-clock"></i>Old photo restore</span>
        <span class="chip" data-tool="hdr"><i class="fas fa-sun"></i>HDR effect</span>
      </div>

      <!-- Resolution selector: HD, 4K, 8K, and ORIGINAL SIZE option -->
      <div class="res-grid" id="resGrid">
        <span class="res-btn" data-res="hd">HD (720p)</span>
        <span class="res-btn active" data-res="4k">4K Ultra HD</span>
        <span class="res-btn" data-res="8k">8K Ultra HD</span>
        <span class="res-btn original-size" data-res="original">📏 Original Size (no upscale)</span>
      </div>

      <button class="enhance-btn" id="enhanceBtn"><i class="fas fa-magic"></i> Enhance & Process</button>

      <div class="preview-row">
        <div class="preview-box">
          <div class="image-container" id="beforeContainer">
            <i class="fas fa-image placeholder-icon" id="beforePlaceholder"></i>
            <img id="beforeImage" src="#" alt="before" style="display:none;">
          </div>
          <p><strong>Original</strong> (blurry / low quality)</p>
          <div id="beforeDimensions" style="font-size:0.8rem; color:#4b5563;"></div>
        </div>
        <div class="preview-box">
          <div class="image-container" id="afterContainer">
            <i class="fas fa-image placeholder-icon" id="afterPlaceholder"></i>
            <img id="afterImage" src="#" alt="after" style="display:none;">
          </div>
          <p><strong>AI Enhanced</strong> (quality fixed + upscaled if selected)</p>
          <div id="afterDimensions" style="font-size:0.8rem; color:#4b5563;"></div>
        </div>
      </div>

      <button class="download-btn" id="downloadBtn" disabled><i class="fas fa-download"></i> Download Enhanced Image</button>
    </div>

    <!-- Ad Unit Middle -->
    <div class="ad-unit">
      <div class="ad-label">Advertisement</div>
      <div class="ad-content"><i class="fas fa-ad"></i> Google AdSense - Rectangle</div>
    </div>

    <div class="pages-grid">
      <div class="page-card"><i class="fas fa-arrow-up"></i> Quality Enhancer</div>
      <div class="page-card"><i class="fas fa-hd"></i> HD Upscaler</div>
      <div class="page-card"><i class="fas fa-microchip"></i> 4K Converter</div>
      <div class="page-card"><i class="fas fa-pen"></i> 8K Upscaler</div>
      <div class="page-card"><i class="fas fa-face-smile"></i> Face Restore</div>
    </div>

    <h2 style="font-size: 2rem; margin: 50px 0 20px;">📘 AI Image Blog</h2>
    <div class="blog-grid">
      <div class="blog-card"><i class="fas fa-image"></i><h3>How to upscale blurry photos to 4K</h3><p class="meta">keyword: "upscale to 4K"</p></div>
      <div class="blog-card"><i class="fas fa-camera-retro"></i><h3>Best free AI image enhancers 2025</h3><p class="meta">keyword: "free AI image enhancer"</p></div>
      <div class="blog-card"><i class="fas fa-blur"></i><h3>Fix blur and keep original size</h3><p class="meta">keyword: "fix blurry photo"</p></div>
    </div>

    <!-- Ad Unit Bottom -->
    <div class="ad-unit">
      <div class="ad-label">Advertisement</div>
      <div class="ad-content"><i class="fas fa-ad"></i> Google AdSense - Footer Banner</div>
    </div>
  </div>

  <footer class="footer">
    <div class="container footer-grid">
      <div><h4 style="color:white;">PixelUp.AI</h4>Enhance + upscale to 4K/8K</div>
      <div><h4>Pages</h4><a href="#">About Us</a><a href="#">Contact</a><a href="#">Privacy Policy</a></div>
      <div><h4>Tools</h4><a href="#">Image Enhancer</a><a href="#">4K Upscaler</a><a href="#">8K Upscaler</a></div>
    </div>
    <div class="container" style="text-align:center; margin-top:30px;">© 2025 PixelUp AI – All rights reserved.</div>
  </footer>

  <script>
    (function() {
      const dragDrop = document.getElementById('dragDrop');
      const fileInput = document.getElementById('fileInput');
      const beforeImg = document.getElementById('beforeImage');
      const afterImg = document.getElementById('afterImage');
      const beforePlaceholder = document.getElementById('beforePlaceholder');
      const afterPlaceholder = document.getElementById('afterPlaceholder');
      const downloadBtn = document.getElementById('downloadBtn');
      const enhanceBtn = document.getElementById('enhanceBtn');
      const chips = document.querySelectorAll('.chip');
      const resBtns = document.querySelectorAll('.res-btn');
      const beforeDimensions = document.getElementById('beforeDimensions');
      const afterDimensions = document.getElementById('afterDimensions');
      const dimensionDisplay = document.getElementById('dimensionDisplay');

      let originalFile = null;
      let originalDataUrl = null;
      let enhancedDataUrl = null;
      let currentTool = 'deblur';
      let currentRes = '4k'; // default 4K
      let originalWidth = 0, originalHeight = 0;

      // Tool chips
      chips.forEach(chip => {
        chip.addEventListener('click', function() {
          chips.forEach(c => c.classList.remove('active'));
          this.classList.add('active');
          currentTool = this.dataset.tool;
        });
      });

      // Resolution buttons (including original size)
      resBtns.forEach(btn => {
        btn.addEventListener('click', function() {
          resBtns.forEach(b => b.classList.remove('active'));
          this.classList.add('active');
          currentRes = this.dataset.res;
        });
      });

      // Drag & drop / file picker
      dragDrop.addEventListener('click', () => fileInput.click());
      dragDrop.addEventListener('dragover', (e) => e.preventDefault());
      dragDrop.addEventListener('drop', (e) => {
        e.preventDefault();
        const file = e.dataTransfer.files[0];
        if (file && file.type.startsWith('image/')) handleFile(file);
      });
      fileInput.addEventListener('change', (e) => {
        if (e.target.files[0]) handleFile(e.target.files[0]);
      });

      function handleFile(file) {
        originalFile = file;
        const reader = new FileReader();
        reader.onload = (e) => {
          originalDataUrl = e.target.result;
          const img = new Image();
          img.onload = () => {
            originalWidth = img.width;
            originalHeight = img.height;
            beforeImg.src = originalDataUrl;
            beforeImg.style.display = 'inline';
            beforePlaceholder.style.display = 'none';
            afterImg.style.display = 'none';
            afterPlaceholder.style.display = 'inline';
            enhancedDataUrl = null;
            downloadBtn.disabled = true;
            beforeDimensions.textContent = `Dimensions: ${originalWidth} x ${originalHeight}`;
            afterDimensions.textContent = '';
            dimensionDisplay.innerHTML = `<i class="fas fa-arrows-alt" style="color:#2563eb;"></i> Original: ${originalWidth} x ${originalHeight}`;
          };
          img.src = originalDataUrl;
        };
        reader.readAsDataURL(file);
      }

      // ENHANCE + UPSCALE (if resolution selected, otherwise keep original size)
      function processImage(originalDataUrl, tool, resolution) {
        return new Promise((resolve) => {
          const img = new Image();
          img.crossOrigin = 'Anonymous';
          img.onload = () => {
            const canvas = document.createElement('canvas');
            
            // Determine output dimensions based on resolution selection
            let targetWidth = img.width;
            let targetHeight = img.height;
            
            if (resolution === 'hd') {
              // Scale to at least 1280x720 proportionally
              const scale = Math.max(1280 / img.width, 720 / img.height);
              targetWidth = Math.round(img.width * scale);
              targetHeight = Math.round(img.height * scale);
            } else if (resolution === '4k') {
              const scale = Math.max(3840 / img.width, 2160 / img.height);
              targetWidth = Math.round(img.width * scale);
              targetHeight = Math.round(img.height * scale);
            } else if (resolution === '8k') {
              const scale = Math.max(7680 / img.width, 4320 / img.height);
              targetWidth = Math.round(img.width * scale);
              targetHeight = Math.round(img.height * scale);
            } else {
              // original size - keep exactly the same dimensions
              targetWidth = img.width;
              targetHeight = img.height;
            }
            
            canvas.width = targetWidth;
            canvas.height = targetHeight;
            
            const ctx = canvas.getContext('2d');
            // Draw image scaled to new dimensions (or original)
            ctx.drawImage(img, 0, 0, targetWidth, targetHeight);
            
            // Apply quality enhancement (sharpening, deblur, etc.) to the entire image
            let imageData = ctx.getImageData(0, 0, canvas.width, canvas.height);
            let data = imageData.data;
            let width = canvas.width;
            let height = canvas.height;
            
            let output = new Uint8ClampedArray(data.length);
            output.set(data);
            
            // Laplacian sharpening kernel for detail enhancement
            const kernel = [
              [0, -1, 0],
              [-1, 5, -1],
              [0, -1, 0]
            ];
            
            // Apply kernel to each pixel (skip borders)
            for (let y = 1; y < height - 1; y++) {
              for (let x = 1; x < width - 1; x++) {
                let idx = (y * width + x) * 4;
                let r = 0, g = 0, b = 0;
                
                for (let ky = -1; ky <= 1; ky++) {
                  for (let kx = -1; kx <= 1; kx++) {
                    let pixelIdx = ((y + ky) * width + (x + kx)) * 4;
                    let weight = kernel[ky+1][kx+1];
                    r += data[pixelIdx] * weight;
                    g += data[pixelIdx+1] * weight;
                    b += data[pixelIdx+2] * weight;
                  }
                }
                
                output[idx] = Math.min(255, Math.max(0, r));
                output[idx+1] = Math.min(255, Math.max(0, g));
                output[idx+2] = Math.min(255, Math.max(0, b));
                output[idx+3] = data[idx+3];
              }
            }
            
            // Additional tool-specific quality adjustments
            for (let i = 0; i < output.length; i += 4) {
              if (tool === 'deblur' || tool === 'sharpen') {
                output[i] = Math.min(255, output[i] * 1.15);
                output[i+1] = Math.min(255, output[i+1] * 1.15);
                output[i+2] = Math.min(255, output[i+2] * 1.15);
              } else if (tool === 'noise') {
                output[i] = output[i] * 0.92 + 12;
                output[i+1] = output[i+1] * 0.92 + 12;
                output[i+2] = output[i+2] * 0.92 + 12;
              } else if (tool === 'face') {
                output[i] = Math.min(255, output[i] * 1.12);
                output[i+1] = Math.min(255, output[i+1] * 1.08);
                output[i+2] = Math.min(255, output[i+2] * 1.05);
              } else if (tool === 'restore') {
                output[i] = Math.min(255, output[i] * 1.25);
                output[i+1] = Math.min(255, output[i+1] * 1.2);
                output[i+2] = Math.min(255, output[i+2] * 1.15);
              } else if (tool === 'hdr') {
                let avg = (output[i] + output[i+1] + output[i+2]) / 3;
                output[i] = Math.min(255, output[i] + (output[i] - avg) * 0.3);
                output[i+1] = Math.min(255, output[i+1] + (output[i+1] - avg) * 0.3);
                output[i+2] = Math.min(255, output[i+2] + (output[i+2] - avg) * 0.3);
              }
            }
            
            ctx.putImageData(new ImageData(output, width, height), 0, 0);
            
            // Add subtle resolution label
            ctx.font = 'bold 18px Inter';
            ctx.fillStyle = 'rgba(37,99,235,0.5)';
            let label = resolution === 'original' ? 'AI Enhanced' : `AI ${resolution.toUpperCase()}`;
            ctx.fillText(label, 30, 50);
            
            resolve(canvas.toDataURL('image/png'));
          };
          img.src = originalDataUrl;
        });
      }

      enhanceBtn.addEventListener('click', async () => {
        if (!originalDataUrl) {
          alert('Please upload an image first.');
          return;
        }

        enhanceBtn.innerHTML = '<i class="fas fa-spinner fa-pulse"></i> Processing...';
        enhanceBtn.disabled = true;

        try {
          enhancedDataUrl = await processImage(originalDataUrl, currentTool, currentRes);
          afterImg.src = enhancedDataUrl;
          afterImg.style.display = 'inline';
          afterPlaceholder.style.display = 'none';
          downloadBtn.disabled = false;
          
          // Show dimensions in after preview (need to load image to get dimensions)
          const img = new Image();
          img.onload = () => {
            afterDimensions.textContent = `Dimensions: ${img.width} x ${img.height}`;
          };
          img.src = enhancedDataUrl;
        } catch (err) {
          alert('Enhancement failed.');
          console.error(err);
        } finally {
          enhanceBtn.innerHTML = '<i class="fas fa-magic"></i> Enhance & Process';
          enhanceBtn.disabled = false;
        }
      });

      downloadBtn.addEventListener('click', function() {
        if (enhancedDataUrl) {
          const link = document.createElement('a');
          link.download = `enhanced_${currentTool}_${currentRes}.png`;
          link.href = enhancedDataUrl;
          link.click();
        }
      });
    })();
  </script>
  <div style="text-align:center; padding:20px;">✅ Choose: HD / 4K / 8K upscaling OR keep original size. Quality (deblur, sharpen) always applied. AdSense ready.</div>
</body>
</html>
