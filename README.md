*,
::after,
::before {
  box-sizing: border-box;
}

$bg_body: #212121;
$bg_gradient_last_color: rgba(0, 212, 255, 1);
$bg_gradient: linear-gradient(
  90deg,
  rgba(2, 0, 36, 1) 0%,
  rgba(52, 9, 121, 1) 37%,
  $bg_gradient_last_color 94%
);

body {
  background-color: $bg_body;
  color: #fff;
  font-family: monospace, serif;
  letter-spacing: 0.05em;
}

h1 {
  font-size: 23px;
}

.form {
