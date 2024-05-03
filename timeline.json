<!DOCTYPE html>
<html>
<head>
    <title>Title</title>
</head>
<body>
    <div id="timeline" style="width: 80%; height: 30px; background-color: #f0f0f0; border-radius: 5px; overflow: hidden;"></div>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const timeline = document.getElementById('timeline');

            // Array of job durations in percentage (sum should be 100%)
            const jobDurations = [30, 50, 20];

            jobDurations.forEach(duration => {
                const job = document.createElement('div');
                job.className = 'job';
                job.style.width = `${duration}%`;
                job.style.height = '100%'; // Set job bar height
                job.style.backgroundColor = '#007bff'; // Set job bar color
                timeline.appendChild(job);
            });
        });
    </script>
</body>
</html>
