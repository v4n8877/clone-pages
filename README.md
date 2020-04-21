## Project Title
CSS PROJECT Bài 40 - Tổng kết và chốt hạ khóa [PRO] MASTER CSS 2018. 
## Getting Started
- Use git clone to copy repository
## Motivation
Try to improve my knowledge about frontend (html, css and javascript).
## Code style
- Using scss.
- Doing a component.
- Don't use library with hmtl css ex: boostrap, material.
- BEM
## Code Example
.banner {
	display: flex;
	justify-content: space-between;
	align-items: center;
  padding:0 15px;
  height: 700px;
	&__about {
		flex-basis: 50%;
		flex-grow: 0.5;
		&--btn {
			text-transform: uppercase;
			line-height: 42px;
	    padding-left: 30px;
	    padding-right: 30px;
	    border: none;
			color: #fff;
			background: -webkit-linear-gradient(0deg, #8490ff 0%, #62bdfc 100%);
			transition: all 0.3s ease 0s;
	    cursor: pointer;
	    position: relative;
	    &:hover {
	    	box-shadow: 0px 20px 20px 0px rgba(132, 144, 255, 0.3);
	    }
		}
		h6 {
			text-transform: uppercase;
  		font-weight: 400;
    	letter-spacing: 2px;
		}
		h1 {
			margin: 20px 0;
	    font-size: 30px;
	    text-transform: uppercase;
		}
		p {
			margin-bottom: 1rem;
		}
	}
	&__img {
		flex-basis: 50%;
		flex-grow: .5;
		display: flex;
		justify-content: center;
		align-items: flex-end;
		img {
			max-width: 400px;
    	height: 450px;
		}
	}
}

## Demo
https://v4n8877-personal.firebaseapp.com
## How to use?
- Open with browser
## Credits
- https://colorlib.com/preview/#personal
