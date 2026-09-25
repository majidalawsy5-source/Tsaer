<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>برنامج الجدول المخصص</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Naskh+Arabic:wght@400;500;600;700&display=swap" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com"></script>
    
    <style>
        body {
            font-family: 'Noto Naskh Arabic', serif;
            background-color: #f3f4f6;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 1.5rem 1rem;
            min-height: 100vh;
            margin: 0;
        }

        .controls-container {
            background-color: white;
            padding: 1.25rem;
            border-radius: 0.75rem;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08);
            margin-bottom: 1.5rem;
            width: 100%;
            max-width: 650px;
        }

        .control-group {
            display: flex;
            align-items: center;
            justify-content: space-between;
            margin-bottom: 0.75rem;
        }

        .control-group:last-child {
            margin-bottom: 0;
        }

        #table-container {
            background-color: #ffffff;
            width: 100%;
            max-width: 700px;
            aspect-ratio: 2.2 / 1;
            border: 5px solid #000000;
            border-radius: 20px;
            overflow: hidden;
            box-sizing: border-box;
            display: grid;
            grid-template-rows: repeat(3, minmax(0, 1fr));
            grid-template-columns: repeat(2, minmax(0, 1fr));
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.12);
        }

        .cell-header {
            grid-column: 1 / -1;
            border-bottom: 5px solid #000000;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 0.25rem 0.5rem;
            overflow: hidden;
        }

        .cell-row2-right {
            grid-column: 1 / 2;
            border-bottom: 5px solid #000000;
            border-left: 5px solid #000000;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 0.25rem 0.5rem;
            overflow: hidden;
        }

        .cell-row2-left {
            grid-column: 2 / 3;
            border-bottom: 5px solid #000000;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 0.25rem 0.5rem;
            overflow: hidden;
        }

        .cell-row3-right {
            grid-column: 1 / 2;
            border-left: 5px solid #000000;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 0.25rem 0.5rem;
            overflow: hidden;
        }

        .cell-row3-left {
            grid-column: 2 / 3;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 0.25rem 0.5rem;
            overflow: hidden;
        }

        .static-text {
            color: #000000;
            white-space: nowrap;
            user-select: none;
            font-weight: inherit;
            line-height: 1;
            flex-shrink: 0;
        }

        .input-text {
            border: none;
            outline: none;
            background: transparent;
            text-align: center;
            width: 100%;
            color: #000000;
            font-family: inherit;
            font-size: inherit;
            font-weight: inherit;
            line-height: 1;
            padding: 0;
            margin: 0;
        }

        .input-text::placeholder {
            color: #888888;
            opacity: 0.75;
        }

        .cell-content {
            display: flex;
            flex-direction: row;
            flex-wrap: nowrap;
            align-items: center;
            justify-content: center;
            gap: 0.35em;
            max-width: 100%;
            white-space: nowrap;
        }

        .unit-input {
            field-sizing: content;
            min-width: 2ch;
            text-align: center;
            width: 12ch;
        }

        input[type=number]::-webkit-inner-spin-button, 
        input[type=number]::-webkit-outer-spin-button { 
            -webkit-appearance: none; 
            margin: 0; 
        }
        input[type=number] {
            -moz-appearance: textfield;
        }

        .action-buttons {
            display: flex;
            gap: 1rem;
            margin-top: 1.5rem;
        }

        .btn {
            padding: 0.75rem 1.75rem;
            border-radius: 0.5rem;
            font-weight: bold;
            color: white;
            cursor: pointer;
            transition: transform 0.1s, background-color 0.2s;
            border: none;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        .btn:active {
            transform: scale(0.97);
        }
        .btn-primary { background-color: #3b82f6; }
        .btn-primary:hover { background-color: #2563eb; }
        .btn-success { background-color: #10b981; }
        .btn-success:hover { background-color: #059669; }

        :root {
            --table-font-size: 24px;
            --table-font-weight: 700;
        }

        .dynamic-font {
            font-size: var(--table-font-size);
            font-weight: var(--table-font-weight);
        }
    </style>
</head>
<body>

    <div class="controls-container">
        <h2 class="text-lg font-bold text-center mb-3 text-gray-800">إعدادات الجدول</h2>
        
        <div class="control-group">
            <label for="fontSize" class="text-sm font-semibold text-gray-700">حجم الخط الأساسي:</label>
            <div class="flex items-center gap-2 w-1/2">
                <input type="range" id="fontSize" min="14" max="42" value="24" class="w-full accent-blue-600">
                <span id="fontSizeDisplay" class="font-mono bg-gray-100 px-2 py-1 rounded text-xs">24px</span>
            </div>
        </div>

        <div class="control-group">
            <label for="fontWeight" class="text-sm font-semibold text-gray-700">سمك الخط:</label>
            <select id="fontWeight" class="border border-gray-300 rounded px-2 py-1 text-sm w-1/2">
                <option value="400">عادي (Regular)</option>
                <option value="500">متوسط (Medium)</option>
                <option value="600">شبه غامق (Semi-Bold)</option>
                <option value="700" selected>غامق (Bold)</option>
            </select>
        </div>
    </div>

    <div id="table-container" class="dynamic-font">
        <!-- الصف الأول: العنوان الممتد -->
        <div class="cell-header">
            <input type="text" id="inputHeader" class="input-text text-center font-bold" placeholder="مربع نص">
        </div>

        <!-- الصف الثاني: العمود الأيمن (١/٤ كغم) -->
        <div class="cell-row2-right">
            <span class="static-text">١/٤ كغم</span>
        </div>

        <!-- الصف الثاني: العمود الأيسر (مربع نص رقمي + د.ع) -->
        <div class="cell-row2-left">
            <div class="cell-content">
                <input type="text" id="inputRow2Left" inputmode="numeric" class="input-text unit-input" placeholder="مربع نص رقمي">
                <span class="static-text">د.ع</span>
            </div>
        </div>

        <!-- الصف الثالث: العمود الأيمن (مربع نص رقمي + غم) -->
        <div class="cell-row3-right">
            <div class="cell-content">
                <input type="text" id="inputRow3Right" inputmode="numeric" class="input-text unit-input" placeholder="مربع نص رقمي">
                <span class="static-text">غم</span>
            </div>
        </div>

        <!-- الصف الثالث: العمود الأيسر (مربع نص رقمي + د.ع) -->
        <div class="cell-row3-left">
            <div class="cell-content">
                <input type="text" id="inputRow3Left" inputmode="numeric" class="input-text unit-input" placeholder="مربع نص رقمي">
                <span class="static-text">د.ع</span>
            </div>
        </div>
    </div>

    <div class="action-buttons">
        <button id="saveBtn" class="btn btn-primary">حفظ كصورة</button>
        <button id="shareBtn" class="btn btn-success">مشاركة</button>
    </div>

    <div id="imageModal" class="fixed inset-0 bg-black bg-opacity-60 hidden items-center justify-center z-50 p-4 transition-opacity">
        <div class="bg-white rounded-xl p-4 max-w-lg w-full flex flex-col items-center shadow-2xl relative max-h-[90vh] overflow-y-auto">
            <button id="closeModalBtn" class="absolute top-2 left-2 text-gray-500 hover:text-gray-800 text-2xl font-bold px-2 py-1">&times;</button>
            <h3 class="text-base font-bold text-gray-800 mb-1">صورة الجدول الجاهزة</h3>
            <p class="text-xs text-gray-600 mb-3 text-center leading-relaxed">
                اضغط على <b>"حفظ في الاستوديو / مشاركة"</b> للحفظ المباشر، أو اضغط مطولاً على الصورة واختر <b>"إضافة إلى الصور"</b>.
            </p>
            
            <div class="border border-gray-200 rounded-lg p-2 bg-gray-50 w-full flex justify-center mb-3">
                <img id="modalImage" class="max-w-full h-auto rounded shadow-sm" alt="جدول الأسعار" />
            </div>

            <div class="flex flex-wrap gap-2 w-full justify-center">
                <button id="modalShareBtn" class="btn btn-success flex-1 min-w-[140px] text-sm py-2">
                    حفظ في الاستوديو / مشاركة
                </button>
                <button id="modalDownloadBtn" class="btn btn-primary flex-1 min-w-[140px] text-sm py-2">
                    تنزيل كملف
                </button>
            </div>
        </div>
    </div>

    <script>
        const fontSizeInput = document.getElementById('fontSize');
        const fontSizeDisplay = document.getElementById('fontSizeDisplay');
        const fontWeightSelect = document.getElementById('fontWeight');
        const root = document.documentElement;

        fontSizeInput.addEventListener('input', function() {
            const size = this.value + 'px';
            root.style.setProperty('--table-font-size', size);
            fontSizeDisplay.textContent = size;
        });

        fontWeightSelect.addEventListener('change', function() {
            root.style.setProperty('--table-font-weight', this.value);
        });

        root.style.setProperty('--table-font-size', fontSizeInput.value + 'px');
        root.style.setProperty('--table-font-weight', fontWeightSelect.value);

        function formatWithSeparators(val) {
            const unformatted = val.replace(/[,٬]/g, '');
            if (!/^[0-9٠-٩]+$/.test(unformatted)) {
                return val;
            }
            let result = '';
            let count = 0;
            for (let i = unformatted.length - 1; i >= 0; i--) {
                if (count > 0 && count % 3 === 0) {
                    result = ',' + result;
                }
                result = unformatted[i] + result;
                count++;
            }
            return result;
        }

        function updateUnitInputWidth(input) {
            if (!input.classList.contains('unit-input')) return;
            const formatted = formatWithSeparators(input.value);
            if (input.value !== formatted) {
                input.value = formatted;
            }
            const val = input.value.trim();
            if (val.length > 0) {
                input.style.width = (val.length + 0.5) + 'ch';
            } else {
                input.style.width = '12ch';
            }
        }

        document.querySelectorAll('.unit-input').forEach(input => {
            updateUnitInputWidth(input);
            input.addEventListener('input', () => updateUnitInputWidth(input));
        });

        async function generateCanvasSnapshot() {
            if (document.fonts) {
                await document.fonts.ready;
            }

            const container = document.getElementById('table-container');
            const rect = container.getBoundingClientRect();
            const actualWidth = rect.width || 700;

            const canvas = document.createElement('canvas');
            const width = 1200;
            const scaleRatio = width / actualWidth;
            const height = Math.round(width / 2.2);
            
            const scale = 2;
            canvas.width = width * scale;
            canvas.height = height * scale;
            
            const ctx = canvas.getContext('2d');
            ctx.scale(scale, scale);

            // 1. خلفية بيضاء صافية
            ctx.fillStyle = '#ffffff';
            ctx.fillRect(0, 0, width, height);

            // 2. إعداد الخطوط والإطار الأسود متناسب مع الحجم
            const lineWidth = 5 * scaleRatio;
            const radius = 20 * scaleRatio;
            ctx.strokeStyle = '#000000';
            ctx.lineWidth = lineWidth;
            ctx.lineCap = 'square';

            // رسم الإطار الخارجي بزوايا دائرية
            ctx.beginPath();
            if (ctx.roundRect) {
                ctx.roundRect(lineWidth / 2, lineWidth / 2, width - lineWidth, height - lineWidth, radius);
            } else {
                const x = lineWidth / 2, y = lineWidth / 2, w = width - lineWidth, h = height - lineWidth, r = radius;
                ctx.moveTo(x + r, y);
                ctx.lineTo(x + w - r, y);
                ctx.arcTo(x + w, y, x + w, y + r, r);
                ctx.lineTo(x + w, y + h - r);
                ctx.arcTo(x + w, y + h, x + w - r, y + h, r);
                ctx.lineTo(x + r, y + h);
                ctx.arcTo(x, y + h, x, y + h - r, r);
                ctx.lineTo(x, y + r);
                ctx.arcTo(x, y, x + r, y, r);
            }
            ctx.stroke();

            // الخط الأفقي الأول
            const y1 = height / 3;
            ctx.beginPath();
            ctx.moveTo(0, y1);
            ctx.lineTo(width, y1);
            ctx.stroke();

            // الخط الأفقي الثاني
            const y2 = (height / 3) * 2;
            ctx.beginPath();
            ctx.moveTo(0, y2);
            ctx.lineTo(width, y2);
            ctx.stroke();

            // الخط العمودي الأوسط
            const xMid = width / 2;
            ctx.beginPath();
            ctx.moveTo(xMid, y1);
            ctx.lineTo(xMid, height);
            ctx.stroke();

            // 3. كتابة النصوص بألوان ومحاذاة مضبوطة
            ctx.fillStyle = '#000000';
            ctx.textAlign = 'center';
            ctx.textBaseline = 'middle';

            const userFontSize = parseInt(fontSizeInput.value, 10) || 24;
            const canvasFontSize = Math.round(userFontSize * scaleRatio);
            const fontWeight = fontWeightSelect.value || '700';
            
            ctx.font = `${fontWeight} ${canvasFontSize}px 'Noto Naskh Arabic', 'Traditional Arabic', serif`;

            const valHeader = document.getElementById('inputHeader').value.trim();
            const valRow2Left = formatWithSeparators(document.getElementById('inputRow2Left').value.trim());
            const valRow3Right = formatWithSeparators(document.getElementById('inputRow3Right').value.trim());
            const valRow3Left = formatWithSeparators(document.getElementById('inputRow3Left').value.trim());

            if (valHeader) {
                ctx.fillText(valHeader, width / 2, y1 / 2);
            }

            ctx.fillText("١/٤ كغم", width * 0.75, y1 + (y2 - y1) / 2);

            const textRow2Left = valRow2Left ? `\u200F${valRow2Left}  د.ع` : "د.ع";
            ctx.fillText(textRow2Left, width * 0.25, y1 + (y2 - y1) / 2);

            const textRow3Right = valRow3Right ? `\u200F${valRow3Right}  غم` : "غم";
            ctx.fillText(textRow3Right, width * 0.75, y2 + (height - y2) / 2);

            const textRow3Left = valRow3Left ? `\u200F${valRow3Left}  د.ع` : "د.ع";
            ctx.fillText(textRow3Left, width * 0.25, y2 + (height - y2) / 2);

            return new Promise((resolve) => {
                const dataUrl = canvas.toDataURL("image/png");
                canvas.toBlob((blob) => {
                    const file = new File([blob], 'جدول-الأسعار.png', { type: 'image/png' });
                    resolve({ dataUrl, file });
                }, 'image/png');
            });
        }

        const imageModal = document.getElementById('imageModal');
        const closeModalBtn = document.getElementById('closeModalBtn');
        const modalImage = document.getElementById('modalImage');
        const modalShareBtn = document.getElementById('modalShareBtn');
        const modalDownloadBtn = document.getElementById('modalDownloadBtn');
        const saveBtn = document.getElementById('saveBtn');
        const shareBtn = document.getElementById('shareBtn');

        let currentFile = null;
        let currentDataUrl = '';

        function openModal(dataUrl) {
            modalImage.src = dataUrl;
            imageModal.classList.remove('hidden');
            imageModal.classList.add('flex');
        }

        function closeModal() {
            imageModal.classList.add('hidden');
            imageModal.classList.remove('flex');
        }

        closeModalBtn.addEventListener('click', closeModal);
        imageModal.addEventListener('click', (e) => {
            if (e.target === imageModal) closeModal();
        });

        async function handleShare() {
            if (!currentFile) return;
            if (navigator.canShare && navigator.canShare({ files: [currentFile] })) {
                try {
                    await navigator.share({
                        title: 'جدول الأسعار',
                        files: [currentFile]
                    });
                } catch (err) {
                    if (err.name !== 'AbortError') {
                        console.error('Share error:', err);
                    }
                }
            } else {
                downloadImage();
            }
        }

        function downloadImage() {
            if (!currentDataUrl) return;
            const link = document.createElement('a');
            link.download = 'جدول-الأسعار.png';
            link.href = currentDataUrl;
            link.click();
        }

        saveBtn.addEventListener('click', async () => {
            const result = await generateCanvasSnapshot();
            currentDataUrl = result.dataUrl;
            currentFile = result.file;

            if (navigator.canShare && navigator.canShare({ files: [result.file] })) {
                handleShare();
            } else {
                openModal(result.dataUrl);
            }
        });

        shareBtn.addEventListener('click', async () => {
            const result = await generateCanvasSnapshot();
            currentDataUrl = result.dataUrl;
            currentFile = result.file;
            openModal(result.dataUrl);
        });

        modalShareBtn.addEventListener('click', handleShare);
        modalDownloadBtn.addEventListener('click', downloadImage);
    </script>
</body>
</html>
