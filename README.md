# learning-react-router
# 1. Create createBrowserRouter and Add React Router provider to your main app
```javascript
import {
  createBrowserRouter,
  RouterProvider
} from 'react-router-dom';

const router = createBrowserRouter([
  {
    path: "/",
    element: <div>Hello world!</div>,
  },
]);

ReactDOM.createRoot(document.getElementById('root')).render(
  <React.StrictMode>
    # React Router Wrapper
    <RouterProvider router={router} />
  </React.StrictMode>,
)
```
