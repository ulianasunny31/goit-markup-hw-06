# goit-markup-hw-01

.picture-list {
display: flex;
flex-wrap: wrap;
gap: 24px;
row-gap: 48px;
}

.picture-list-item {
width: calc((100% - 48px) / 3);
transition: box-shadow;
}

.picture-links {
display: block;
transition: box-shadow 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

.picture-links:hover,
.picture-links:focus {
box-shadow: 0px 2px 1px 0px rgba(46, 47, 66, 0.08),
0px 1px 1px 0px rgba(46, 47, 66, 0.16),
0px 1px 6px 0px rgba(46, 47, 66, 0.08);
}

.pictures-titles {
font-size: 20px;
letter-spacing: 0.02em;
font-weight: 500;
color: var(--navy-blue);
line-height: 1.2;
margin-bottom: 8px;
}

.pictures-p {
font-size: 16px;
font-weight: 400;
line-height: 1.5;
letter-spacing: 0.02em;
color: var(--slate);
}

.p-list-container {
border: 1px solid var(--cornflower);
padding: 32px 16px;
border-top: none;
}

.overlay {
position: relative;
overflow: hidden;
}

.p-overlay {
color: var(--cloud);
font-size: 16px;
font-weight: 400;
line-height: 1.5;
letter-spacing: 0.02em;
top: 0;
left: 0;
width: 100%;
height: 100%;
background-color: var(--iris);
position: absolute;
padding: 40px 32px;
transform: translateY(100%);
transition: transform 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

.picture-links:hover .p-overlay,
.picture-links:focus .p-overlay {
transform: translateY(0%);
}
